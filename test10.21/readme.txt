10.21�ղ���
�ڱ��ش���һ���ļ��н�test10.21 ,�ļ�����Ӧ����5��html�ļ�,�ֱ�����Ϊ1.html��.�ٴ���һ��readme.txt�ļ�,���⼸��������������,���html�е�js������������·�.

1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:
    <h1 id="h1"></h1>
    <script>
        var h1 = document.getElementById('h1');
        var a = 'a';
        var b = 'b';
        h1.innerHTML = a.concat(b);
    </script>

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
    <h2 id="h2"></h2>
    <script>
        var h2 = document.getElementById('h2');
        var a = '87w';
        h2.innerHTML =  a.substr(0,2).padEnd(6,'0');
    </script>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
    <h3 id="h3"></h3>
    <script>
        var h3 = document.getElementById('h3');
        var a = 79387.348;
        h3.innerHTML = a.toFixed(2);
    </script>

4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
    <h4 id="h4"></h4>
    <script>
        var h4 = document.getElementById('h4');
        var a = 'img/head/,icon/1.jpg,';
        var b = a.split(',');
        c = b[0]+b[1];
        h4.innerHTML = c;
    </script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��:
    <h5 id="h5"></h5>
    <script>
        var h5 = document.getElementById('h5');
        var a = prompt('������֤�� EEee');
        h5.innerHTML =  a.toLowerCase();

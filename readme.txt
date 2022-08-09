数据

manage.py migrate
manage.py makemigrations
manage.py migrate

sqlite to mysql

1.manage.py dumpdata > data.json

2.改配置 setting.py

3.执行建表 manage.py migrate

4.manage.py loaddata data.json
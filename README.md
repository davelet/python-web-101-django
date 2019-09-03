# 准备
```
pip install setuptools

pip install django

pip install djangorestframework

pip install tensorflow

pip install tensorflow-hub

pip install qiniu

pip install bottleneck

pip install mysqlclient

pip install pillow

pip install django-rest-elasticsearch

pip install apscheduler

pip install django-apscheduler
```
# 启动
python manage.py runserver

# 数据模型
```
python manage.py makemigrations goods_detection_server

python manage.py sqlmigrate goods_detection_server 0001

python manage.py migrate
```



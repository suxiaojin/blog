# blog
 2016-07-03 16:00

 适用于Python-2.7

 使用方法

 pip install django==1.8.3

 pip install DjangoUeditor==1.8.143

 git clone https://github.com/fengmo/blog.git

 cd blog

 ./manager.py makemigrations 

 ./manager.py migrate

 ./manager.py createsuperuser

 ./manager.py collectstatic 

 
 安装nginx,并配置static

 centos-yum安装

 yum install nginx
 
 centoos-源码安装

 .....

 启动nginx

 /etc/init.d/nginx start

 ./manager.py runserver 

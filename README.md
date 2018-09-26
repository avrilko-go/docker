# docker


1. docker pull registry.cn-hangzhou.aliyuncs.com/avrilko1/lnmp:v8

2. docker run -it -p 3308:3306 -p 80:80 -p 24:22  -v $PWD/7.2:/etc/php/7.2 -v $PWD/mysql:/etc/mysql -v $PWD/nginx:/etc/nginx -v $PWD/../code:/web 829c1c7ec930  /bin/bash


3. ssh 账号root密码123456


4. mysql 账号test 密码 test 可远程连接

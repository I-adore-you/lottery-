# 基础镜像
FROM mysql:5.7

# author
MAINTAINER bytemecc

ENV MYSQL_ROOT_PASSWORD "自己的密码"

# 执行sql脚本
COPY  ./db/  /docker-entrypoint-initdb.d/

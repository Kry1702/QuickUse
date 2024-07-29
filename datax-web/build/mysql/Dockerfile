FROM m.daocloud.io/docker.io/library/mysql:8.0.39
#FROM m.daocloud.io/docker.io/library/mysql:8.0.35

MAINTAINER Kry497 <mail@kry.cn>

ENV LANG C.UTF-8

RUN  ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime 
   
ADD ./sql /data/sql

COPY entrypoint.sql  /docker-entrypoint-initdb.d/


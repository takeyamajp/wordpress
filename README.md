FROM centos:centos7  
MAINTAINER "Hiroki Takeyama"

ENV REQUIRE_SSL true

ENV WORDPRESS_DB_HOST mysql  
ENV WORDPRESS_DB_USER user  
ENV WORDPRESS_DB_PASSWORD user  
ENV WORDPRESS_DB_NAME db  
ENV WORDPRESS_DB_CHARSET utf8mb4

VOLUME /wordpress

EXPOSE 80  
EXPOSE 443

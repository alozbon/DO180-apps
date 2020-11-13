FROM ubi7/ubi:7.7

MAINTAINER antoniojlozano <antoniojlozano@gmail.com>

RUN yum install -y httpd && yum clean all

ADD paint.tar /var/www/html

EXPOSE 8080

#USER apache

CMD ["httpd", "-D", "FOREGROUND"]

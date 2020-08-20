FROM centos:latest
MAINTAINER Choi IH
RUN yum -y install httpd
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
COPY httpd.conf /etc/httpd/conf/httpd.conf
EXPOSE 8080-9000/tcp

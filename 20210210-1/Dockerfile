FROM centos:centos7
RUN yum -y update
RUN yum -y install httpd
EXPOSE 80
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]

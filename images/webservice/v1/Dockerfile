#skalluru/webservice:v1
FROM centos
RUN yum install httpd -y
COPY index.html /var/www/html/index.html
EXPOSE 80
CMD /usr/sbin/httpd -DFOREGROUND


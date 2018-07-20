FROM centos
RUN yum install httpd -y
RUN echo Hello World - v1 >/var/www/html/index.html
CMD /usr/sbin/httpd -DFOREGROUND

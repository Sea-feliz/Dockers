FROM centos
RUN yum install httpd -y
EXPOSE 80
RUN echo Hey how are you >>/var/www/html/index.html
COPY run.sh /
RUN chmod +x /run.sh
CMD  /run.sh
 

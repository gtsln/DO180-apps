FROM ubi7/ubi:7.7
MAINTAINER "hai vo" quang.hai.vo@ibm.com
LABEL "A custom Apache container based on UBI 7"
RUN yum install -y httpd 
RUN echo "Hello from Dockerfile" > /var/www/html/index.html
EXPOSE 80
ENTRYPOINT ["httpd"]
CMD ["-D", "FOREGROUND"]


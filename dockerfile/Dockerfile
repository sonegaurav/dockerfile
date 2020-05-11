FROM ubuntu:16.04 

RUN apt-get update 
RUN apt-get install apache2 -y
COPY ./1.html    /var/www/html
EXPOSE 80 
CMD [“apache2ctl”, “-D”, “FOREGROUND”]


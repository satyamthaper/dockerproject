From ubuntu:latest
RUN apt-get update -y
RUN apt-get install apache2 -y
COPY ./mywebsite/* /var/www/html/
CMD ["apachectl", "-D", "FOREGROUND"]
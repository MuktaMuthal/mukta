FROM docker.io/ubuntu 

RUN  touch  day{1..10}.xls
RUN mkdir unnati

RUN apt update -y
RUN apt install apache2 -y
RUN  echo "Hello world " > /var/www/html/index.html

CMD ["apache2ctl","-D","FOREGROUND"]

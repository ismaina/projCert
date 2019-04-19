FROM devopsedu/webapp

MAINTAINER Maina Wanjau (maina.wanjau@gmail.com/mwanjau@safaricomdigitalacademy.co.ke)

ADD . /var/www/html
RUN rm /var/www/html/index.html
EXPOSE 80 8080 443

CMD ["apachectl", "-D", "FOREGROUND"]

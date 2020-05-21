FROM devopsedu/webapp

ADD website /usr/local/tomcat/webapps

RUN rm /var/www/html/index.html

CMD apachectl -D FOREGROUND

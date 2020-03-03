FROM devopsedu/webapp
RUN mkdir /var/www/html
ADD website /var/www/html
RUN rm /var/www/html/index.html
CMD apachectl -D FOREGROUND

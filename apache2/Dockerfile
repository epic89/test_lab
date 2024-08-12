FROM ubuntu:24.04

RUN apt-get update 

RUN apt-get install wget apache2 apache2-utils php libapache2-mod-php php-mysqlnd php-pgsql php-cli php-odbc php-pdo-dblib php-mbstring -y

RUN apt autoremove -y && apt clean

RUN mkdir /var/www/html/adminer && wget https://www.adminer.org/latest.php -O /var/www/html/adminer/index.php

EXPOSE 81

CMD ["apache2ctl", "-D", "FOREGROUND"]

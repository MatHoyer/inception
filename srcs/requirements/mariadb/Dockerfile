FROM debian:buster

RUN apt update && apt upgrade -y && apt-get install mariadb-server -y

COPY conf/mariadb.conf	/etc/mysql/mariadb.conf.d/mariadb.conf

CMD [ "./tools/mariadb.sql"]
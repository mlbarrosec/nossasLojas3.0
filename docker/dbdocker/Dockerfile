FROM mariadb

ENV MYSQL_DATABASE=ourstore \
    MYSQL_ROOT_PASSWORD=root

ADD ./ourstore.sql /docker-entrypoint-initdb.d
EXPOSE 3306
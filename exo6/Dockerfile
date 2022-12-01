FROM mysql/mysql-server:5.7

ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes
ENV MYSQL_USER=marvin
ENV MYSQL_PASSWORD=nsapool421
ENV MYSQL_DATABASE=nsapool

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/

COPY ./sql-scripts/nsapool.sql .
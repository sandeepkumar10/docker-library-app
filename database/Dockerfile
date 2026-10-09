FROM mysql/mysql-server:5.7

LABEL author="Sandeep Kumar"

WORKDIR /docker-entrypoint-initdb.d

EXPOSE 3306

COPY database.sql ./database.sql 

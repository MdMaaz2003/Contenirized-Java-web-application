FROM mysql:8.0.33

LABEL maintainer="Vprofile"
LABEL description="Dockerfile for Vprofile MySQL database"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql



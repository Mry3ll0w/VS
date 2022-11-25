FROM --platform=linux/amd64 mysql:latest
COPY db.sql /docker-entrypoint-initdb.d
ENV MYSQL_ROOT_PASSWORD=root

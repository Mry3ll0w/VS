FROM --platform=linux/amd64 mariadb:latest
COPY db.sql /docker-entrypoint-initdb.d
ENV MARIADB_ROOT_PASSWORD=root

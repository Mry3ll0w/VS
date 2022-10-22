FROM mariadb:latest
RUN apt-get update
RUN apt-get install -y iputils-ping
RUN apt install -y dnsutils
COPY db.sql /docker-entrypoint-initdb.d
EXPOSE 3306
ENV MARIADB_ROOT_PASSWORD=root
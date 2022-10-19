FROM mariadb:latest
COPY db.sql /docker-entrypoint-initdb.d
EXPOSE 3306
#metemos en entry point para que 
ENV MARIADB_ROOT_PASSWORD=root
FROM ubuntu:latest
COPY . .
RUN apt-get update
#Necesitamos dentro de la app:
#
RUN apt install -y python3
RUN apt install -y python3-pip
RUN apt install -y default-libmysqlclient-dev
RUN apt install -y mariadb-client
RUN pip install -r requirements.txt

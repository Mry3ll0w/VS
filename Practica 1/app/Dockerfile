FROM ubuntu:latest
COPY . .
RUN apt-get update
RUN apt-get install -y iputils-ping
RUN apt install -y dnsutils
RUN apt install -y python3
RUN apt install -y python3-pip
RUN apt install -y default-libmysqlclient-dev
RUN apt install -y mariadb-client
RUN pip install -r requirements.txt
CMD python3 web_project/manage.py runserver 0.0.0.0:8800
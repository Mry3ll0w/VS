FROM ubuntu:latest
COPY . .
RUN apt-get update -y
RUN apt install python3 -y
RUN apt install python3-pip -y
RUN apt install -y default-libmysqlclient-dev
RUN pip install -r requirements.txt
WORKDIR /web_project

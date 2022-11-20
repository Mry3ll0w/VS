FROM --platform=linux/amd64 ubuntu:latest
COPY . .
RUN apt-get update -y
RUN apt install python3 -y
RUN apt install python3-pip -y
RUN apt install -y default-libmysqlclient-dev
RUN pip install -r requirements.txt
WORKDIR /web_project
CMD python3 manage.py runserver 0.0.0.0:8800

#COmando para acceder en mac al contenedor minikube service [nombre pod] [n_replica]
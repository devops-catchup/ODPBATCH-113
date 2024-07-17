FROM ubuntu

MAINTAINER swapnilmahajan30@gmail.com

RUN apt-get update 

WORKDIR /sample-second

RUN apt-get install -y git && apt-get install -y net-tools

RUN apt-get install -y vim && apt-get install -y nginx

RUN apt-get install -y openssh-server

COPY index.html /var/www/html

ADD jdk-11.0.20_linux-x64_bin.tar.gz /sample-second

ENTRYPOINT service nginx start && bash



FROM mono:latest

RUN apt-get update
RUN apt-get install unzip

RUN useradd -m -d /server pufferd
WORKDIR /server

USER pufferd
ENV HOME /server

FROM ubuntu:20.04

RUN apt-get update

RUN apt-get install unzip

FROM mono:latest
RUN useradd -m -d /server pufferd
WORKDIR /server

USER pufferd
ENV HOME /server

FROM ubuntu:20.04
Maintainer Devansh Agarwal

RUN useradd -m -d /server pufferd
WORKDIR /server


RUN apt-get uzip

RUN apt update &&//
    apt install dirmngr gnupg apt-transport-https ca-certificates software-properties-common &&//
    apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF &&//
    apt-add-repository 'deb https://download.mono-project.com/repo/ubuntu stable-focal main' &&//
    apt install mono-complete

USER pufferd
ENV HOME /server

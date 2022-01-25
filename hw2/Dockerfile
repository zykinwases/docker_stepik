FROM ubuntu:16.04

ARG UID=1000

RUN apt-get update && apt-get -y install nano

ENV EDITOR=nano

WORKDIR /home/stepik

USER $UID

VOLUME /home/stepik

ENTRYPOINT nano

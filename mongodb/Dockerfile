FROM ubuntu:14.04
MAINTAINER Daniel Almaguer <danielalmaguer@gmail.com>

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update

RUN apt-get install -y sudo software-properties-common mongodb

RUN mkdir -p /data/db
EXPOSE 27017
EXPOSE 28017

CMD ["usr/bin/mongod"]


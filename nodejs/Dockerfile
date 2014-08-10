FROM ubuntu:14.04
MAINTAINER Daniel Almaguer <danielalmaguer@gmail.com>

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update

#Utilities
RUN apt-get install -y sudo software-properties-common nodejs nodejs-dev npm ruby

RUN ln -s /usr/bin/nodejs /usr/bin/node

RUN npm install -g pm2@latest
RUN gem install sass

EXPOSE 3000

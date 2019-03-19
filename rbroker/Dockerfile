FROM balenalib/raspberrypi3-python:3.6.6-stretch-build
#FROM linusmotu/arm-pi-datascience:1.0.0
#FROM balenalib/amd64-debian:stretch-build

EXPOSE 5011

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

#RUN apt-get update
#RUN apt-get install python3-dev
#RUN apt-get install python3-pip

ADD ./requirements.txt /usr/src/app/requirements.txt

RUN pip3 install -r requirements.txt
FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get install python3.6
RUN apt-get clean

WORKDIR /app
COPY . /app
ENV DEBUG=True
EXPOSE 90
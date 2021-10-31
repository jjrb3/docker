FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get install python3.6

WORKDIR /app
COPY . /app
ENV DEBUG=True
EXPOSE 90
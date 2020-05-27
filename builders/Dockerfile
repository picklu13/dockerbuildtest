FROM ubuntu:18.04

RUN dpkg --add-architecture i386 && apt-get update
	 

RUN apt-get install -y maven

WORKDIR /app

RUN mvn clean package

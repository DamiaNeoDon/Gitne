FROM ubuntu:latest

LABEL version="001"
LABEL maintainer="mr.damian.frac@gmail.com"

RUN apt-get update && apt-get upgrade -y

RUN apt-get install nginx -y

EXPOSE 90

CMD [ "nginx","-g","daemon off;"]

#koment 

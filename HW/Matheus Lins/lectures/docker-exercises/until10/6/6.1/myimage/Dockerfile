FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y iputils-ping vim
CMD ["ping", "127.0.0.1", "-c", "30"]

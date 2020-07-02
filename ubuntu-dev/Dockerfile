FROM ubuntu:20.04

RUN apt-get update && apt-get upgrade -y \
    && apt-get install -y \
        curl \
        zip \
        iputils-ping \
        telnetd \
        iproute2 \
        apache2-utils \
        vim \
        openssh-client \
    && apt-get update && apt-get upgrade -y \
    && apt-get autoclean && apt-get autoremove -y

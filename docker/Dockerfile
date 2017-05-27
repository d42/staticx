FROM debian:8

RUN echo 'deb-src http://deb.debian.org/debian jessie main' >> /etc/apt/sources.list

RUN apt-get update \
    && apt-get install -y \
        gcc \
        libtar-dev \
        musl \
        musl-dev \
        musl-tools \
        scons \
    && rm -rf /var/lib/apt/lists/*

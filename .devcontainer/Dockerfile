FROM registry.suse.com/bci/golang:1.23

RUN apt-get update
RUN apt-get install vim sudo curl -y

RUN useradd -m -s /bin/bash -G sudo coder
USER coder

RUN zypper --non-interactive install -y tar git gzip openssh

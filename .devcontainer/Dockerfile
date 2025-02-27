FROM registry.suse.com/bci/golang:1.23

RUN useradd -m -s /bin/bash -G docker coder
USER coder

RUN zypper --non-interactive install -y tar git gzip openssh

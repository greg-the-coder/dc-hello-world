FROM registry.suse.com/bci/golang:1.23

RUN useradd -m -s /bin/bash -G 1001 coder
USER coder

RUN zypper --non-interactive install -y tar git gzip openssh

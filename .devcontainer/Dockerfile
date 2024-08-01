ARG VARIANT="bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/rust:1-${VARIANT}

RUN apt-get update && \
    apt-get install -y python3-pip python3-dev && \
    pip3 install jupyter 

RUN cargo install evcxr_jupyter



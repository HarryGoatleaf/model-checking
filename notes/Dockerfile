FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# install requirements
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y pandoc


# install quarto
RUN git clone https://github.com/quarto-dev/quarto-cli
WORKDIR quarto-cli
RUN ./configure-linux.sh

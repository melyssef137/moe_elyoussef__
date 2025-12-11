FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    nodejs \
    npm

RUN pip3 install flask
RUN npm install -g @vue/cli

WORKDIR /workspace
CMD ["bash"]

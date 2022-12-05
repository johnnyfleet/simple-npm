FROM mcr.microsoft.com/devcontainers/javascript-node:14
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install libpcsclite1 libpcsclite-dev pcscd \
    && rm -rf /var/lib/apt/lists/*
# Use the official Debian Bullseye image as a base
FROM debian:bullseye

# Update the package list and install netcat
RUN apt-get update && \
    apt-get install -y curl netcat podman && \
    rm -rf /var/lib/apt/lists/*

RUN curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
RUN chmod 700 get_helm.sh
RUN ./get_helm.sh

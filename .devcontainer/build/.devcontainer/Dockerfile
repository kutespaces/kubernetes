# Use the official Debian Bullseye image as a base
FROM debian:bullseye

# Update the package list and install netcat
RUN apt-get update && \
    apt-get install -y netcat && \
    rm -rf /var/lib/apt/lists/*

RUN curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash && chmod +x /usr/local/bin/helm

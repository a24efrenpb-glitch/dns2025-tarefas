FROM debian:12

RUN apt update  && apt install -y \
    procps \
    iproute2 \
    iputils-ping \
    bind9utils \
    dnsutils \
    && rm -rf /var/lib/apt/lists/*


CMD ["tail", "-f", "/dev/null"]

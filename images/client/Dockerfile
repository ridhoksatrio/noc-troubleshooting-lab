FROM ubuntu:24.04
RUN apt-get update && apt-get install -y iproute2 iputils-ping tcpdump dnsutils \
  ppp pppoe ffmpeg mtr-tiny curl iperf3 smcroute vim nano && rm -rf /var/lib/apt/lists/*
CMD ["sleep","infinity"]

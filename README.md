# DNSHTTPS
dockerized DNS over HTTPS using pi-hole through cloudflared proxy-dns

adapted from https://visibilityspots.org/dockerized-cloudflared-pi-hole.html and his neat cloudflared container

For administration and configuration see CjK’s Admin Handbook.

Getting started
Optionally add / modify pi-hole configuration / dnsmasq-config in the directories ./config/pihole or ./config/dnsmasq.
Bring both containers the docker network up: docker-compose up -d

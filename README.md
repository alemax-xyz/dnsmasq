## Dnsmasq docker image

Dnsmasq is a lightweight, easy to configure, DNS forwarder and DHCP server.
It is designed to provide DNS and optionally, DHCP, to a small network.
It can serve the names of local machines which are not in the global DNS.
The DHCP server integrates with the DNS server and allows machines with
DHCP-allocated addresses to appear in the DNS with names configured either
in each host or in a central configuration file.

NOTE: `NET_ADMIN` capability is required.

This image is based on official dnsmasq package for Ubuntu Bionic with LUA support and is built on top of [clover/base](https://hub.docker.com/r/clover/base/).

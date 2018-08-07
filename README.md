# CoreDNS for my home

This sets up a DNS server with DNS-over-TLS to Cloudflare's 1.0.0.1.

I use this with [Kubix MicroOS](https://en.opensuse.org/Kubic:MicroOS) to create a DNS appliance out of an old computer.

- 1.1.1.1 didn't work me, maybe because I'm on ATT?
- If you're on Ubuntu 18.04 don't forget to [take care of systemd-resolved](https://askubuntu.com/questions/907246/how-to-disable-systemd-resolved-in-ubuntu)

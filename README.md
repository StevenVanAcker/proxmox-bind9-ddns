Set up a selfhosted DNS resolver with dynamic DNS (RFC2136) support using BIND9.
Primarily created to be used on Proxmox VE, but I assume this will work in other situations as well.

Intended usage:

    bash <(curl -fsSL https://raw.githubusercontent.com/StevenVanAcker/proxmox-bind9-ddns/refs/heads/master/setup-bind9.sh) --domain mylab.internal --yes

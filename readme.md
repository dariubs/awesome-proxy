# Awesome Proxy

A collaborative list of awesome proxy servers and resources. Feel free to contribute!

## What is

> A proxy server, also known as a "proxy" or "application-level gateway", is a computer that acts as a gateway between a local network (for example, all the computers at one company or in one building) and a larger-scale network such as the internet. [^1](https://kb.iu.edu/d/ahoo)

## Types

- [Proxy server (Forward Proxy) ](https://en.wikipedia.org/wiki/Proxy_server)
- [Reverse Proxy](https://en.wikipedia.org/wiki/Reverse_proxy)

![Forward Proxy vs Reverse Proxy](https://i.stack.imgur.com/0qpxZ.png)

## Protocols

- SOCKS Proxy
- HTTP Proxy
- SSL Proxy
- FTP Proxy
- DNS Proxy
- Anonymous Proxy

## Proxy server (Forward Proxy)

> A proxy server that passes unmodified requests and responses is usually called a gateway or sometimes a tunneling proxy.

> A forward proxy is an Internet-facing proxy used to retrieve data from a wide range of sources.

- [Proxy Server - wikipedia](https://en.wikipedia.org/wiki/Proxy_server)
- [What is Proxy - quora](https://www.quora.com/What-is-proxy)

### Popular Proxy servers

- [squid](http://www.squid-cache.org/)

## Reverse Proxy

> A reverse proxy is usually an internal-facing proxy used as a front-end to control and protect access to a server on a private network. A reverse proxy commonly also performs tasks such as load-balancing, authentication, decryption or caching.

- [What Is a Reverse Proxy Server?](https://www.nginx.com/resources/glossary/reverse-proxy-server/)

### Popular Reverse Proxies

- [Nginx](http://nginx.net/)
- [Apache](http://wiki.apache.org/cocoon/ApacheModProxy)
- [HAProxy](http://haproxy.1wt.eu/)

## SOCKS Proxy

> SOCKS is an Internet protocol that exchanges network packets between a client and server through a proxy server. SOCKS5 additionally provides authentication so only authorized users may access a server. Practically, a SOCKS server proxies TCP connections to an arbitrary IP address, and provides a means for UDP packets to be forwarded. [wikipedia](https://en.wikipedia.org/wiki/SOCKS)

### SOCKS protocol

- [SOCKS Protocol version 5 - rfc 1928](https://www.ietf.org/rfc/rfc1928.txt)
- [SOCKS Protocol version 4](https://www.openssh.com/txt/socks4.protocol)

### Popular Implementations of SOCKS server

- [Shadowsocks](https://shadowsocks.org/en/index.html) - A secure socks5 proxy, designed to protect your Internet traffic.
- [Dante](https://www.inet.no/dante/) - A free SOCKS server.
- [microsocks](https://github.com/rofl0r/microsocks) - Tiny, portable SOCKS5 server with very moderate resource usage.

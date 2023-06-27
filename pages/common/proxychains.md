# proxychains

> A tool that forces any TCP connection made by any given application to follow through proxy like TOR or any other SOCKS4, SOCKS5 or HTTP(S) proxy.

- Run firefox through proxy specified by proxychains.conf

`proxychains firefox example.com`

- Use different configuration file then proxychains.conf

`proxychains -f /etc/proxychains-other.conf firefox example.com`

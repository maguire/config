1. Launch Ubuntu EC2 Image
2. sudo apt-get install squid
3. Replace squid.conf





diff /etc/squid3/squid.conf /etc/squid3/squid.conf.bak 
1060c1060
< http_access allow all
---
> http_access deny all
2681c2681
< # forward_max_tries 10
---
> # forward_max_tries 25
6865c6865
< forwarded_for off
---
> # forwarded_for on
7162d7161
< 

# ScapeticalDNS
A no-logging public DNS with ads and tracking domains blocked, recursive resolver, so queries don't get forwarded to upstream servers. This started as a personal project of mine because my ISP's DNS is unreliable and blocks certain sites, and I don't want to use public DNS servers run by big corporations. I originally planned to just run a local DNS server at home, but later decided that I also want to use my DNS when I was not home. I don't guarantee a 100% uptime as I might make few changes here and there (and ofcourse, if I ran out of money :P). So what's the difference between this and other public DNS servers? There isn't much difference honestly, I created this so that I can control my own blocklist, and to learn about secure DNS protocols. <br> <br>
<i>Indonesian users: most ISP's spoof your dns in order to comply with internetpositif, regular plaintext DNS probably won't work for you.</i>

## Supported Protocols
* IPv4 DNS
* DNS-over-TLS
* DNS-over-HTTPS
* DNSCrypt v2
* Anonymized DNS Relay

## Plaintext DNS (IPv4)
`128.199.154.79`

## DNS-over-TLS
`dns.scapetical.com port 853`

## DNS-over-HTTPS
### URI
`https://dns.scapetical.com/dns-query `
### DNS Stamp (to use with dnscrypt-proxy)
`sdns://AgMAAAAAAAAADjEyOC4xOTkuMTU0Ljc5ID4aGg9sU_PpekktVwhLW5gHBZ7gV6sVBYdv2D_aPbg4EmRucy5zY2FwZXRpY2FsLmNvbQovZG5zLXF1ZXJ5`

## DNSCrypt v2
Note : uses port 54 <br>
`sdns://AQMAAAAAAAAAETEyOC4xOTkuMTU0Ljc5OjU0IH1m6BHRmB7aPTWhUlPWXs96vv9omdCGYn4IbaIOw-bTHjIuZG5zY3J5cHQtY2VydC5zY2FwZXRpY2FsLmNvbQ`

## Anonymized DNS Relay
`sdns://gRExMjguMTk5LjE1NC43OTo1NA`  <br> <br> <br>

To verify if DNS is working, visit <a href="http://dnsleaktest.com/">dnsleaktest</a> and click on standard test. If everything's working hostname should say dns.scapetical.com

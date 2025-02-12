# trackerslist

## Download Indexes

1. [index/all.txt](index/all.txt)
1. [index/udp.txt](index/udp.txt)
1. [index/ip.txt](index/ip.txt)
1. [index/archived.txt](index/archived.txt)

### Notes

* A bot automatically checks the trackers and updates the lists.
* Trackers with the same domain or pointing to the same IP address are removed. Check out the [blacklist](blacklist.txt).
* Trackers are sorted by popularity and latency (from best to worst).
* WebSocket trackers (AKA WebTorrent, ws, wss) are supported by few clients. [More info](https://webtorrent.io).
* Lists with IP addresses can be shorter because [Cloudflare IPs](https://www.cloudflare.com/ips/) are removed.

# GameCache Docker Compose

Uses [steamcache:steamcache-dns](https://github.com/steamcache/steamcache-dns) and [steamcache:monolithic](https://github.com/steamcache/monolithic) to make various CDN caches.

This brings up:

* Sniproxy
* Steamcache DNS
* Steamcache Monolithic

This binds to the host and uses ports 53 (dns), 80 (cache), 443 (ssl), so you might need to disable dnsmasq if running Ubuntu 18.04.


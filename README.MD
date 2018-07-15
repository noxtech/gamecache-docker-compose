# GameCache Docker Compose

Uses steamcache:steamcache-dns and steamcache:generic to make a collection of game server caches.

This brings up:

* DNS
* Steam cache
* Origin cache
* Blizzard cache
* Uplay cache
* Windows cache

This also binds it to a specific interface. You may need to enable promiscuous mode so that multiple IPs / MAC addresses can reside on one interface.

Configure your DNS to point to 192.168.1.253 (or change all the IPs in docker-compose.yml as required).

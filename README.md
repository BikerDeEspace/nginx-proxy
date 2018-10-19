# nginx-proxy

Credit to François Romain, take a look to: 

https://medium.com/@francoisromain/host-multiple-websites-with-https-inside-docker-containers-on-a-single-server-18467484ab95

## Start

```bash
#GET SOURCES
git clone https://github.com/BikerDeEspace/nginx-proxy.git /srv/www/nginx-proxy

cd /srv/www/nginx-proxy

#CREATE NETWORK
docker network create nginx-proxy

#START CONTAINERS
docker-compose up -d
```
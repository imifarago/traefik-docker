# Traefik

Traefik docker-compose project a konténer alapú fejlesztéshez

## Nézd át a config filet (traefik.toml)

## Létre kell hozni a saját docket networkot: `docker network create web`
Ezek után, azok a web serverek, amiket el akarsz érni a proxyn keresztül, a network web-re kell tenni

## Indítsd el: `docker-compose up -d`
Build nem kell, nincs dockerfile, a teljes leírója a docker-compose.yml-ben van

## Dashboard elérés
Ha mindent jól csináltál akkor a http://localhost:8080 -on elérhetővé válik a traefik dashboardod

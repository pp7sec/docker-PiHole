create folder and yml file
```sh
mkdir docker-PiHole && cd docker-PiHole && touch docker-compose.yml
```

start docker
```sh
docker compose up -d
```

set password
```sh
docker compose exec pi-hole sudo pihole -a -p
```

restart
```sh
docker restart pi-hole
```

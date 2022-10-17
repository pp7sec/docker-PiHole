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

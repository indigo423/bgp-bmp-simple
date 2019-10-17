# Usage

```
docker-compose up -d
```

Show BMP messages

```
docker-compose logs -f bmpd
```

Announce routes

```
docker-compose exec r01 gobgp global rib add 192.168.255.0/24 -a ipv4
```

Remove routes

```
docker-compose exec r01 gobgp global rib del 192.168.255.0/24 -a ipv4
```

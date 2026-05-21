# Docker Start
<pr>


## docker run/stop
```
docker compose up -d
docker compose down
```

## Dump database
### Linux/wsl
```
docker exec -t <CONTAINER_NAME> pg_dump -U postgres <DATABASE_NAME> > dump.sql
```
### Windowns
```
docker exec -t <CONTAINER_NAME> pg_dump -U postgres <DATABASE_NAME> | Out-File dump.sql
```
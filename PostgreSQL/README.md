# Docker Start
<pr>


## docker run
```
docker compose up -d
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
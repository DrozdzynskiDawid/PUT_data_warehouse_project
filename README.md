# PUT_data_warehouse_project

## Running docker container for Postgres:

```bash
docker run -d --name timescaledb -e POSTGRES_PASSWORD=password -e POSTGRES_DB=postgres -p 5432:5432 timescale/timescaledb:latest-pg14
```

## Checking if postgres installed properly:
```bash
docker exec -it timescaledb psql -U postgres -d postgres
```
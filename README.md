# Start Open Metadata

By default, Open Metadata Ingestion service (a.k.a Airflow) run on 8080. Therefore, we need to make sure that Port 8080 on machine is not busy at all.

To download the newest docker-compose.yaml file, please visit:
[Open Metadata Release](https://github.com/open-metadata/OpenMetadata/releases)

# Run

With MySQL
```bash
docker compose -f docker-compose.yml up
```

With Postgres
```bash
docker compose -f docker-compose-postgres.yml up
```

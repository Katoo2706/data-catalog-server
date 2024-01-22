# Start Open Metadata

Note: By default, Open Metadata Ingestion service (a.k.a Airflow) run on 8080. Therefore, we need to make sure that Port 8080 on machine is not busy at all.

To download the newest docker-compose.yaml file, please visit:
[Open Metadata Release](https://github.com/open-metadata/OpenMetadata/releases)

# Deployment guide
[Documents](https://docs.open-metadata.org/v1.1.x/quick-start/local-docker-deployment)

# Run

With MySQL
```bash
docker compose -f docker-compose.yml up
```

With Postgres
```bash
docker compose -f docker-compose-postgres.yml up
```

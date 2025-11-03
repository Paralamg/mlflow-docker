# MLflow Tracking Server with MinIO и PostgreSQL (Docker Compose)

## Running the Project

1. Copy and set up `.env` file
```shell
cp .env.temple .env
```

2. Start all services:
```shell
docker compose up -d
```

3. Open in your brouser

Mlflow - [http://127.0.0.1:5000](http://127.0.0.1:5000)

Minio - [http://127.0.0.1:9000](http://127.0.0.1:9000)
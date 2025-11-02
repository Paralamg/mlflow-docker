FROM ghcr.io/mlflow/mlflow:v3.5.1

# Устанавливаем зависимости для PostgreSQL и MinIO
RUN pip install --no-cache-dir \
    psycopg2-binary==2.9.10 \
    boto3==1.35.30

USER 1001

WORKDIR /home/mlflow

EXPOSE 5000
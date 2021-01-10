# airflow-deploy
Docker Image, Docker compose for Airflow 2.0.0

This docker compose file include: Airflow 2.0.0, Redis, Postgres \
Mode: Celery Cluster

Start all services: `docker-compose up -d` \

Custom FERNET_KEY, to generate new FERNET_KEY : openssl rand -base64 32 \
replace FERNET_KEY to .env file

# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.


```cmd
docker compose up -f docker/docker-compose.db.yml -d

docker compose -f docker-compose.yml -f docker-compose.s3.yml up
```

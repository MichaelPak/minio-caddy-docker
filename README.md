minio-caddy-docker
==================

Small project to launch [minio](https://github.com/minio/minio) - AWS S3 compatible file storage, with [caddy](https://github.com/mholt/caddy) as web server.

Launch
------
First you need to change directive and email (for letsencrypt) in `Caddyfile`. After you can start `docker-compose`:

```bash
docker-compose up
```

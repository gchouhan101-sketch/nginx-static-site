# NGINX Static Site with CI

This repo contains a tiny static site served by NGINX inside a Docker container.

## 🧪 Run Locally

```bash
docker build -t nginx-static .
docker run -p 8080:80 nginx-static
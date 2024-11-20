# QUIC

Nginx with HTTP/3 sample config

### Setup
Create a `.env` file and replace default values with your domain and email
```bash
cp .env.example .env

vim .env
```
Edit and replace your domain in `nginx.conf`
```bash
vim nginx.conf
```
Start the nginx with docker compose
```bash
docker compose up -d
```

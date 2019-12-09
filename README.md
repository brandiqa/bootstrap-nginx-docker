# BOOTSTRAP CSS + NGINX + DOCKER

Simple Nginx server docker container running a static Bootstrap template - `startboostrap-heroic-features`

## How to run

You will need Docker on your machine.

```bash
# Build Image
docker build -t bootstrap-nginx

# Run container
docker run -d -p 80:80 bootstrap-nginx

# Confirm container is running
docker container ls
```

Open your browser at localhost or specify public DNS or IP address to confirm that the web server is running.

## LICENSE

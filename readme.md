# Laravel in Docker

This repo is meant to be a bare-bones vanilla install of Laravel runnable in Docker.
Use it as a reference or starting point as needed.
It uses the latest version of PHP, MySQL, and Apache


## Development Environment
To get your local development environment running, run the following command:



```bash
docker-compose up -d
# now point your web-browser to 127.0.0.1
```

## Terminal Access
To get terminal access on your webserver:

1. Get the name of the container of the php container:
```bash
docker ps
```
2. Attach to the bash terminal of the php container:
```bash
docker exec -i -t <name_of_container> /bin/bash
```


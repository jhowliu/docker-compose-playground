# docker-compose-playground

## docker-compose.yml:

- build: build from "Dockerfile"
- image: build from image 
- ports: bind host with container port (host:container)
- volumes: it will mount host folder on container folder. (If you code changed in your host, container also changed)
- env_file: you can give a environment file to your service.
- enviroment: Or you can use this arg to set enviroment params directly.

## Usage

start:
<code>docker-compose up -d</code>

stop and remove container:
<code>docker-compose down</code>

check service environments:
<code>docker-compose run web env</code>

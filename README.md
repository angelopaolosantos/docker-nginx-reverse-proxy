# AWS Webserver

AWS Webserver is a simple web server to use on any system with Docker installed. An NGINX docker image is used as a reverse proxy for multiple web app containers.

## Requirements

Docker and docker compose must be installed on your server of choice.

## Usage

Start Proxy App container

```bash
npm run start:proxy
```

Start Website1 App Container

```bash
npm run start:website1
```

Stop Proxy App Container

```bash
npm run stop:proxy
```

Start Website App Container

```bash
npm run stop:website1
```

Hot reload Nginx config files.

```bash
npm run reload:proxy
```


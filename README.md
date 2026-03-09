# Our Application

This is the dockerized "Our Application" tutorial app. It includes the app source code, a Dockerfile, and instructions for building and running the container image.

## Prereqs

- Docker installed and running
- A terminal for linux commands like WSL

## Build the docker image

Run the following command in the project directory

```bash
docker build -t getting-started .
```

## Run the docker image

```bash
docker run -dp 3000:3000 getting-started
```

## Open browser to http://localhost:3000

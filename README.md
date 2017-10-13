# dataunity-deploy-docker
Docker Compose deployment config.

## Prerequisites
Please install the following:
- Docker
- Docker-Compose

## Configuration
Environment files must be made to hold keys for things like cloud storage.

TODO: add more details here.

## Directory structure
Make sure the Data Unity projects to deploy are in sibling directories to this deployment directory.

## Running
To run dev version:
```docker-compose -f docker-compose.yml -f docker-compose.dev.yml up```

To run production version:
```docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d```

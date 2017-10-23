# dataunity-deploy-docker
Docker Compose deployment config.

## Prerequisites
Please install the following:
- Docker
- Docker-Compose

## Configuration
Environment files must be made to hold keys for things like cloud storage.

TODO: add more details here.

### Logging in
Add your web url as an authorised url to any login servces you're using with Data Unity. E.g. log into Google Developer console and add your url for your Google project if you plan to log in with Google.

## Directory structure
Make sure the Data Unity projects to deploy are in sibling directories to this deployment directory.

## Running
To run dev version:
```docker-compose -f docker-compose.yml -f docker-compose.dev.yml up```

To run production version:
```docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d```

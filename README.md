# Description

This is just a very basic example of SSO.

# Installation

You will need at least Node 16 installed and Docker.

First we need to install the projects dependencies, run the following command:

```
yarn
```

Then we can run:

```
docker-compose up
```

It might be needed to generate Prisma Client and run migrations, you will have to log into the docker container and run the commands from inside:

```
docker-compose exec api sh
yarn prisma migrate dev
```

# otterDocs

## Repository for Otterplan's engineering related guides

# Getting Started

## Requirements

- [Docker](https://docs.docker.com/engine/installation/)
- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [Node 7.x.x](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/docs/install/)
- A virtual machine, like [VirtualBox](https://www.virtualbox.org/wiki/VirtualBox)

## Repos

- [OtterDB](https://github.com/Otterplan/otterDB): Connect platform database
- [OtterAPI](https://github.com/Otterplan/otterAPI): Connect Platform API Interface
- [Vendor-Platform](https://github.com/Otterplan/Vendor-Platform): Web Consumer App
- [Bridal-Platform](https://github.com/Otterplan/Bridal-Platform): Coming soon...

## Setup

- Clone all the above repos
- Follow repo steps in order

## OtterDB

Follow the [docs](https://docs.docker.com/machine/overview/) but here are the basics
- Run Docker
- Navigate to your local OtterDB folder
- `docker-machine create --driver virtualbox default`
- `docker-machine env default`
- `eval "$(docker-machine env default)"`
- `docker-compose up --build`

Seed data
- coming soon...

Troubleshooting
- Check if your machine is running with `docker-machine ls`
- Restart your machine with `docker-machine start default`
- `eval "$(docker-machine env default)"`
- `docker-compose up --build`

## otterAPI

Make sure otterDB is setup and running
- Runs on port `3000` so make sure it is free
- `yarn install`
- `npm run start:watch`

## Vendor-Platform

Make sure both otterDB and otterAPI are up and running
- Runs on port `3020` so make sure it is free
- `yarn install`
- `yarn start:dev`




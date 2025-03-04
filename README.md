# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Team Name: La Verdadera Destreza

## Team members

- [Peng Jiang](https://github.com/PengJiang-Victor)
- [Jialiang Tang](https://github.com/JialiangTang1)
- [Yuquan Hu](https://github.com/N-A-E-S)
- [Henry Yu](https://github.com/ky2389)

## Product vision statement

**A prototype MongoDB-based online trading platform exclusive for NYU students to buy and sell second-hand items.**

## User stories

[click to jump to the user stories issues](https://github.com/software-students-spring2025/2-web-app-la-verdadera-destreza/issues)

## Steps necessary to run the software

## Prerequisites
- Python 3.11 or higher
- Docker Desktop installed

## Clone the repository
Clone the repository by this command line:

```sh
git clone https://github.com/software-students-spring2025/2-web-app-segfaultsquad.git <your_dirname>
```

## Set up Docker
1. Build and start the containers using Docker Compose:

```sh
docker run -d -p 27017:27017 --name=mongo-example mongo:latest
```

## connect to mongoDB database
```sh
docker exec -it mongo-example mongosh
```

## Use the application
After running this command, MongoDB will be running in a Docker container, accessible on localhost:27017, and it will be running on http://127.0.0.1:5000


## Task boards

[Click to jump to status board.](https://github.com/orgs/software-students-spring2025/projects/91/views/2)

# rabbitmq with docker-compose
rabbitmq server with management via docker compose
[![Build Status](https://files.ariadata.co/file/ariadata_logo.png)](https://ariadata.co)

![](https://img.shields.io/github/stars/ariadata/dc-rabbitmq.svg)
![](https://img.shields.io/github/watchers/ariadata/dc-rabbitmq.svg)
![](https://img.shields.io/github/forks/ariadata/dc-rabbitmq.svg)

### This needs : [dockerhost](https://github.com/ariadata/dockerhost-sh) with non-root user

---
#### 1- Clone this repository :
```sh
git clone -b main https://github.com/ariadata/dc-rabbitmq dc-rabbitmq && cd dc-rabbitmq
cp env.example .env
```
---
#### 2- Make `data` and `logs` directory :
```sh
mkdir -p {data,logs}
```
#### 3- Find `uid` and `gid` and modify .env file :
```sh
id
nano .env
```
#### 4- Run docker-compose stack:
```sh
docker compose up -d
```
#### 5- Enjoy!

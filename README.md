# WordPress Docker Compose

![build](https://github.com/liemlylac/wordpress-docker-compose/workflows/build/badge.svg)
[![Mit License](https://img.shields.io/github/license/liemlylac/wordpress-docker-compose)](https://github.com/liemlylac/wordpress-docker-compose/blob/master/LICENSE)

Sample Wordpress docker-compose for local development

## Infomation
1. wordpress@latest: running in http://localhost:8080
1. phpmyadmin/phpmyadmin: running in http://localhost:8888
1. mysql@v5.7

## Usage
### First time
Clone this repository

```bash
git clone https://github.com/liemlylac/wordpress-docker-compose
```

change dir to `wordpress-docker-compose`

```bash
cd wordpress-docker-compose
```

Pull docker image and start container

```bash
docker-compose up
```

`Ctl` + `C` to stop running container when you are attaching

### Start containers
Start all container without attach

```bash
docker-compose up -d
```

### Stop containers
Stop all running container

```bash
docker-compose stop
```

### Delete containers
Stop all running container

```bash
docker-compose stop
```
Stop and delete all container

```bash
docker-compose down
```


## Environment
OS: Windows 10 1909 (build 18363.657)
Docker: 19.03.5 (build 633a0ea)
Docker Compose: 1.25.4 (build 8d51620a)
Docker Desktop: 2.2.0.3 (build 42716)

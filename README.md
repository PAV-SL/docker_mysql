# Docker MYSQL development

## Create volume 
`docker volume create mysql-storage`

## Create network
`docker network create -d bridge devnet`

## Run
`docker-compose up -d`

## Stop
`docker-compose down -v`

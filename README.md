# go-docker-deploy-boilerplate
- VPS(Conoha)
- golang
- docker
- docker-compose

# Get started
Before starting, you need to create a server on Conoha VPS,
and set up an ssh keys.

## For local
`docker-compose build`
`docker-compose up -d`

## For prod
`docker-compose -f docker-compose.prod.yml build`
`docker-compose -f docker-compose.prod.yml up -d`

# Reference
- [Docker MachineでMacからVPS上のDockerへアプリをデプロイしよう](https://qiita.com/momotaro98/items/5b902afea3530b6f0b93#mac%E3%81%8B%E3%82%89docker-compose%E3%81%A7%E3%82%A2%E3%83%97%E3%83%AA%E3%82%92%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4)


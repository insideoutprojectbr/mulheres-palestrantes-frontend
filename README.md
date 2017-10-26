# mulheres-palestrantes-frontend

Nova versão do site mulheres-palestrantes usando o [Vue.js](https://vuejs.org/).
Esse projeto foi gerado com o [vue-cli](https://github.com/vuejs/vue-cli).

## Instalação

O ambiente de desenvolvimento da aplicação utiliza [Docker](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/) e [Docker-Compose](https://docs.docker.com/compose/install/).

A aplicação é configurada através de variáveis de ambiente.
Para isso crie o arquivo `.env` através do arquivo [`.env.sample`](.env.sample).

```
  docker-compose up # constrói e executa os containers da aplicação e executa o servidor local na porta 5000
```

## Deploy

```
docker-compose exec web npm run build # executa o build para produção com minificação
docker-compose exec web npm run build --report # executa o build para produção e exibe relatório
```

## Testes

```
npm run unit # executa os testes unitários da aplicação
```

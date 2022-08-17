# Farme Tracking Project!

Aplicação desenvolvida pela WiTrybe company, ultilizando inteligência atificial para automatizar o processo de plantação, realiza todo o monitorament das ilhas, através de medições e imagens.

## Tecnologias

* Apache Maven
* Docker
* Docker compose
* Java
* Spring web
* Spring data MongoDB
* jUnit
* Mockito
* MongoDB
* Heroku

## Como usar


No seu terminal digite:
```
git clone git@github.com:DavioLopes/Farm_Tracking.git

cd Farm_Tracking
```

## Inicializando a aplicação

Já na pasta raiz do projeto use o comando:

```
docker-compose up

```

## Testando a aplicação

Raiz do projeto use o comando:

```
mvn test
```

# [Link da aplicação no heroku](https://www.measure-shelter.herokuapp.com)


## API Endpoints

A aplicação contém os seguintes endpoints:

# Ilha endpoint

| Method | Description |
|---|---|
| `GET - localhost:8888/ilhas` | Retorna todas as ilhas. |
| `GET - localhost:8888/ilhas/{id}` | Retorna ilha por id. |
| `POST - localhost:8888/ilhas` | Cadastra uma nova ilha no banco de dados. |
| `DELETE - localhost:8888/ilhas/{id}` | Remove uma ilha do banco de dados. |
| `PUT - localhost:8888/ilhas/{id}` | Atualiza uma ilha no banco de dados. |
| `PATCH - localhost:8888/ilhas/{id}/status` | Atualiza o status da ilha por id. |



# Medicoes endpoint

| Method | Description |
|---|---|
| `GET - localhost:8888/medicoes` | Retorna todas as medicoes. |
| `GET - localhost:8888/medicoes/{id}` | Retorna medicoes por id. |
| `POST - localhost:8888/medicoes` | Cadastra uma nova medicao no banco de dados. |
| `DELETE - localhost:8888/medicoes/{id}` | Remove uma medicao do banco de dados. |
| `PUT - localhost:8888/medicoes/{id}` | Atualiza uma medicao no banco de dados. |


# Imagens endpoint

| Method | Description |
|---|---|
| `GET - localhost:8888/imagens` | Retorna todas as imagens. |
| `GET - localhost:8888/imagens/{id}` | Realiza download de uma imagem através do id. |
| `POST - localhost:8888/imagens/{nome}` | Realiza o upload de uma nova imagem. |



# twitter-py
App Python com o objetivo de consumir a API REST do Twitter, através da biblioteca Tweepy, persistinto os Top Trends no MongoDB.

## Tecnologias 📚

- Python 3.8.x
- FastAPI
- MongoDB

## Requisitos ✋

- Docker
- Docker compose

## Instalação 💽

Instale o [Docker](https://www.docker.com) e [Docker compose](https://docs.docker.com/compose/) no seu computador.

## Rodando a aplicação 🛸

```sh
poetry shell
python main.py
```

Acesso o [Swagger UI](http://localhost:8000/docs) para listar todos os endpoints.

Use `Ctrl+C` para finalizar o processo servidor.

## Rodando os testes 🧪

```sh
poetry shell
pytest
```

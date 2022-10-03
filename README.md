# FastAPI - POC


Repositório para testar uma Prova de Conceito do framework web em Python [FastAPI]


### Processo _burro_

Após ter o código pronto para ser executado (em ambiente de produção) execute
`docker build -t fastapi-image .` para criar uma imagem do container e execute executando
o comando `docker run -d --name fastapi -p 8081:8081 fastapi-image`.

### Executando

Para executar a página na web basta acessar a url no formato
[http://localhost/items/5?q=somequery](http://localhost/items/5?q=somequery).





[FastAPI]: https://fastapi.tiangolo.com/

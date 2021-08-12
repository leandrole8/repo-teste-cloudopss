# Repositorio para teste CloudOpss

Esse repositorio foi criado para a execução do teste utilizando docker com imagens wordpress e mysql

## Passos seguidos

- Para a criação do teste proposto primeiramente verifiquei no dockerhub uma imagem adequada para o wordpress.

- Logo após criei o diretorio de pastas necessárias para montar os arquivos que fariam parte de todo o processo.


## Simulando a execução

- Foi criado um arquivo `docker-compose.yml` na raiz do projeto com os comandos para construir a aplicação utilizando as imagens: `mysql:5.7` e `wordpress:5.6.0-php7.3-apache`.

- Com o arquivo criado o proximo passo pensado foi em executa-la através do terminal utilizando o comando:

`docker-compose up -d`

Esse comando irá fazer o pull das imagens contidas no arquivo `docker-compose.yml` tornando o serviço acessivel através do `localhost:8000`

## Considerações

Escolhi utilizar um arquivo docker-compose pela maneira mais dinamica que achei para criar as rotinas a serem executadas de forma automatizadas.
# ead_php_alura_lumen

> Projeto referente a [este](https://cursos.alura.com.br/course/php-micro-framework-lumen-api-rest) curso.

## Setup

1. Criar `.env`
```sh
cp .env.example .env
```

2. Baixar dependências
```sh
composer i # php 7.4 com pdo e pdo_sqlite
```

3. Criar banco
```sh
php artisan migrate
```
> Caso queira popular previamente use ``php artisan db:seed`` logo após


## Run

- Iniciar servidor
```sh
php -S localhost:8080 -t public
```

## Anotações

- *HATEOAS*: links nos recursos para navegação, facilitando o cliente navegar pela API sem conhecimento prévio.
- [JWT](https://jwt.io/libraries): Estratégia de autenticação sem sessão para API REST
    > Foi utilizado o `firebase/php-jwt`

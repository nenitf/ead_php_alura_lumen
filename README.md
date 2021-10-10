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

## Run

- Iniciar servidor
```sh
php -S localhost:8080 -t public
```

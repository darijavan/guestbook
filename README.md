# Guestbook app with Symfony 5.0.11 (In Progress)

Guestbook app made with Symfony 5.0.11

## Setup

- If you don't have Symfony CLI, just install it [Symfony CLI](https://symfony.com/download)

- Install all composer dependencies by running in the root folder the following command in command prompt

```bash
composer install
```

- Configure database connection in .env file in the root folder

- Create database

```bash
symfony console database:create
```

- Migrate database

```bash
symfony console doctrine:migrations:migrate
```

## Stat dev server

To start the development server, run

```bash
symfony server:start
```

## Goal

This is my first attempt to learn symfony and to create a symfony app by following the **"Symfony 5 The Fast track"** book by _Fabien Potencier_, available at [Zlibrary](https://b-ok.africa/book/5498684/633b30)

## Author

👤 **Hajanirina Ridjvan Randrianandraina**

# Symfony Test

## Опис
Цей проєкт є тестовим додатком на основі Symfony. Він містить базову конфігурацію та функціонал для автентифікації користувачів через JWT.

## Встановлення та запуск

### 1. Клонування репозиторію
```sh
git clone https://github.com/oleksandr-kipz/symfony-test
cd symfony-test
```

### 2. Встановлення залежностей

Завантажте та встановіть [Composer](https://getcomposer.org/download/), якщо він ще не встановлений.

Після цього виконайте команду для встановлення залежностей:
```sh
composer install
```

### 3. Встановлення JWT-аутентифікації
```sh
composer require lexik/jwt-authentication-bundle
```

### 4. Запуск локального сервера
```sh
symfony server:start
```

## Документація API
Документацію до API можна переглянути за наступним посиланням:
[Postman Documentation](https://documenter.getpostman.com/view/41954431/2sAYX9keu2)

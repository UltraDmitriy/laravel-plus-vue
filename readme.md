# Laravel-plus-vue

## Проект с бэкендом на Laravel и фронтендом на фреймворке Vue.js

## Особенности

- Маршруты API для получения данных с бэкенда
- Авторизация и регистрация с помощью Laravel Sanctum
- Миграции для базы данных и сидеры для начального наполнения

## Технологии

В проекте использованы технологии:

- Laravel - PHP-фреймворк бэкенда
- Vue.js - фреймворк для SPA
- Vuex - state management
- Laravel Mix - Надстройка на Webpack для сборки фронта
- Twitter Bootstrap - UI компоненты для приложения

## Установка

Запуск сервисов из docker-compose

```sh
cd laravel-plus-vue
docker-compose up --d
```

Для сборки фронтенда

```sh
npm run prod
```

# Laravel

Данный репозиторий предназначен для инициализации пустого проекта, который содержит в себе:
 - [Laravel 11.9](https://github.com/laravel/framework/releases/tag/v11.9.1)

Для инициализации проекта, необходимо произвести установку зависимостей через Composer, создать `.env` файл, а также инициализацию ключа приложения:

```bash
$ composer require --dev
Search for a package: [НАЖМИТЕ ENTER]
$ cp .env.example .env
$ php artisan key:generate
```

Проект готов для дальнейшей настройки...

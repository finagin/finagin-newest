<h1><a href="https://Finag.in">Finag.in</a> <sub><sup>My website repository</sup></sub></h1>

[![Software License][ico-license]](LICENSE)
[![StyleCI][ico-styleci]][link-styleci]

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Installation](#installation)
  - [Development](#development)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation
### Development
* Клонировать репозитарий
* Установить **Php 7.1** ```brew install php71```
* Установить **Composer** ```brew install composer```
* Создать конфиг ```cp .env.exmaple .env```
* Установить **Mysql** ```brew install mysql```
* Установить **Valet** ```composer global require laravel/valet```
* Запустить в папке проекта ```composer install```
* Сгенерировать ключ ```php artisan key:generate```
* Запустить миграции ```php artisan migrate```
* Установить глобальные зависимости ```npm install -g yarn```
* Установить локальные зависимости проекта ```yarn```
* Собрать фронт ```npm run watch```
* Подключить **Valet** ```valet link website```

## License

The MIT License ([MIT](https://opensource.org/licenses/MIT)). Please see [License File](LICENSE) for more information.

[ico-license]: https://img.shields.io/github/license/mashape/apistatus.svg

[ico-styleci]: https://styleci.io/repos/148273158/shield
[link-styleci]: https://styleci.io/repos/148273158

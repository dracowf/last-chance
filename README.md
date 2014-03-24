### Продукт в разработке
Для продакшн-использования пока не готов :)

- Описать, как менять shortname для disqus (сейчас хардкод для `bevisblog.disqus.com`)

- Создать rss общий и на каждую категорию

- Сохранять html статей

- Добавить gh-deploy

----

## Запуск
```
git clone git@github.com:bevis-ui/bevis-stub.git your-project
cd your-project
make
```
Команда `make` выкачает все необходимые инструменты, соберет единственную страницу и запустит локальный сервер.

Откройте в браузере `http://localhost:8080/`

## Как сделать ещё один блок?
Запустить команду и ответить на вопрос:
```shell
make block
# Введите имя блока: <ИМЯ БЛОКА>
```
После на файловой системе станет доступна директория с файлами блока `/pages/<ИМЯ БЛОКА>`.

Успехов! :)


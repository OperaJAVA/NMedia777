# Домашнее задание к занятию «7. Retrofit (CRUD)»

Выполненное задание прикрепите ссылкой на ваши GitHub-проекты в личном кабинете студента на сайте [netology.ru](https://netology.ru).

**Важно**: ознакомьтесь со ссылками на главной странице [репозитория с домашними заданиями](../README.md).

**Важно**: если у вас что-то не получилось, оформите Issue. [Шаблон для оформления](../report-requirements.md).

## Как сдавать задачи

1. Откройте ваш проект с предыдущего ДЗ (можно взять код из лекции).
1. Сделайте необходимые коммиты.
1. Сделайте пуш. Удостоверьтесь, что ваш код появился на GitHub.
1. Ссылку на ваш проект прикрепите в личном кабинете на сайте [netology.ru](https://netology.ru).
1. Выполните все задачи, чтобы получить зачёт по теме.

## Задача №1. Buggy Server

### Легенда

На лекции мы организовали только обработку позитивного сценария: нам приходят ответы с кодом 2xx, и мы можем обработать тело ответа (если оно есть).

Давайте рассмотрим альтернативный, не очень частый сценарий: в 50 % случаев сервер будет присылать не 2xx коды ответа.

Возьмите сервер из каталога [server](server) и реализуйте обработку подобного рода ошибок. Как реализовать ошибку, вы решаете сами.

**Необязательно**: посмотрите в приложениях Android, как реализована обработка подобных ошибок с точки зрения интерфейса: дают ли пользователю элементы управления для повторения запроса. Попробуйте их реализовать.

Примечание*: стандартная CRUD-функциональность должна по-прежнему работать.

Опубликуйте изменения в виде Pull Request в вашем проекте на GitHub.

В качестве результата пришлите:
1. Ссылку на PR GitHub-проект в личном кабинете студента на сайте [netology.ru](https://netology.ru).
1. Текстовое описание, почему вы реализовали обработку ошибок именно с помощью этих UI-элементов.

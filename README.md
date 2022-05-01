# Otus-2019: Web-python course.

```text
Курс "Web-python" от "Otus" - это не только "Web" и далеко не только "Python".
```

## Домашние задания

Материал авторский.

```text
Замечание: в части документации не прогружаются изображения. Физически они находятся в папках README.files в каждом репозитории. Исправлю верстку позже.
```

* [Анализ кода Python на Python ч.1](https://github.com/BorisPlus/otus_webpython_001) и [ч.2](https://github.com/BorisPlus/otus_webpython_002) - решение различных задач статического анализа кода. Основное напрвление [ч.1.](https://github.com/BorisPlus/otus_webpython_001) - рефакторинг предоставленного педагогом исходного кода, где был смешан дублированый функционал. Но главным обстоятельсвом, как оказалось потом ("ой, ничего непонятно в коде"), было - "Сомнения есть? Тимлид ответит тебе."
* [Проект на Flask](https://github.com/BorisPlus/otus_webpython_004) - пример "простого" приложения на Flask с задействованием связи "many-to-many". Моя фишка - наполнение тестовых данных сведениями с сайта МВидео (приложена отдельная документация).
* [Проект ORM](https://github.com/BorisPlus/otus_webpython_002) - пример-проект объектно-реляционной связки объектов классов (сущностей) Python3 и таблиц (сущностей) БД SQLite (реализация без метаклассов). Много рассуждений и текста. `QLite - ORM for SQLite, as lite ORM for lite SQL` - проверяющему понравилось.
* [WSGI](https://github.com/BorisPlus/otus_webpython_003) - в рамках изучения стандарта взаимодействия между Python-программой, выполняющейся на стороне сервера, и самим веб-сервером, реализовал "свой" фреймворк ["dummy_wsgi_framework"](https://github.com/BorisPlus/dummy_wsgi_framework) для произвольных веб-приложений и внес его в реест [PyPi](https://pypi.org/project/dummy_wsgi_framework/). Можно использовать параметры в запросах к страницам. Генерация HTTP заголовков позволила достаточно просто реализовать Basic HTTP Auth. В последвии добавил возможность задействования шаблонизатора Jinja2.
* [Проект на Django](https://github.com/BorisPlus/otus_webpython_006) - переработан проект на Flask. Задействуется Django Class Based Views, фишка - свой Django Widget [admin_img_widget](https://github.com/BorisPlus/otus_webpython_006/blob/master/README.files/images/screenshots/admin_img_widget.png) и "свои" декораторы для полей в админ-панели. Привожу их в пример . Также заполняется тестовыми данными с сайта МВидео. Про возможность создания комманд Django-Management я тогда не ведал.
* [ORM Django.](https://github.com/BorisPlus/otus_webpython_016) - как можно (и НУЖНО) повлиять на генерируемые Django запросы к базам данных. 
* [Немного Frontend.](https://github.com/BorisPlus/otus_webpython_013) - CSS, JS. Шрифты (ох уж эта буква "Ё" на устройствах Мак)
* [Немного Frontend непосредственно в Django.](https://github.com/BorisPlus/otus_webpython_007_008) - CSS для разных устройств (десктоп \ мобильные), , взаимодействие по REST API. 
* [Еще Frontend.](https://github.com/BorisPlus/otus_webpython_019_frontend) - в рамках данного блока домашних работ был сделан проект для подключения модераторами на своих сайтах формы информирования пользователем о наличии опечаток, подготовлен [для него Backend](https://github.com/BorisPlus/otus_webpython_019_backend). Вылилось в отдельный проект [BugReport](https://github.com/BorisPlus/BugReport).
* [Webpack](https://github.com/BorisPlus/otus_webpython_018) - как собрать весь JS в один проект. 
* [Проект Redis](https://github.com/BorisPlus/otus_webpython_020_021) - пример многоочередной обработки задач (Redis Queue), заключающийся в проверке активности Интернет-ресурсов и -сервисов. 
* [Проект Сelery](https://github.com/BorisPlus/otus_webpython_020_021_celery) - пример запуска в Django асинхронной задачи на стороне сервера (не путать с AJAX на стороне пользователя) с использованием Сelery. 
* [Проект Сelery](https://github.com/BorisPlus/otus_webpython_020_021_celery) - пример запуска в Django асинхронной на стороне сервера с использованием Сelery. 
* [Проект React](https://github.com/BorisPlus/otus_webpython_023) - основы основ NPM и React
* [Проект взаимодействие пользовательского React с серверным Django](https://github.com/BorisPlus/otus_webpython_025) - форма с чатом.
* [Промежуточный вариант курсовой работы Django <-=-> (Redux & React \ Vue)](https://github.com/BorisPlus/otus_webpython_027)

## Курсовой проект

* [Django <-=-> (Redux & React)](https://github.com/BorisPlus/otus_webpython_030) - форма с чатом, авторизация посредством Django, взаимодействие Django сервера и (Redux & React) происходит по REST API с использованием JWT. 


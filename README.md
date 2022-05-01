# Otus-2019: Web-python course.

```text
Курс "Web-python" от "Otus" - это не только "Web" и далеко не только "Python".
```

## Домашние задания

Материал авторский.

```text
Замечание: в части документации не прогружаются изображения. 
Физически они находятся в папках README.files в каждом репозитории. 
Исправлю верстку позже.
```

* [Анализ кода Python на Python ч.1](https://github.com/BorisPlus/otus_webpython_001) и [ч.2](https://github.com/BorisPlus/otus_webpython_002) - решение различных задач статического анализа кода. Основное напрвление [ч.1.](https://github.com/BorisPlus/otus_webpython_001) - рефакторинг предоставленного педагогом исходного кода, где был смешан дублированый функционал. Но главным обстоятельсвом, как оказалось потом ("ой, ничего непонятно в коде"), было - "Сомнения есть? Тимлид ответит тебе."
* [Проект на Flask](https://github.com/BorisPlus/otus_webpython_004) - пример "простого" приложения на Flask с задействованием связи "many-to-many". Моя фишка - наполнение тестовых данных сведениями с сайта МВидео (приложена отдельная документация).
* [Проект ORM](https://github.com/BorisPlus/otus_webpython_002) - пример-проект объектно-реляционной связки объектов классов (сущностей) Python3 и таблиц (сущностей) БД SQLite (реализация без метаклассов). Много рассуждений и текста. _QLite - ORM for SQLite, as lite ORM for lite SQL_ - проверяющему понравилось.
* [WSGI](https://github.com/BorisPlus/otus_webpython_003) - в рамках изучения стандарта взаимодействия между Python-программой, выполняющейся на стороне сервера, и самим веб-сервером, реализовал "свой" фреймворк ["dummy_wsgi_framework"](https://github.com/BorisPlus/dummy_wsgi_framework) для произвольных веб-приложений и внес его в реест [PyPi](https://pypi.org/project/dummy_wsgi_framework/). Можно использовать параметры в запросах к страницам. Генерация HTTP заголовков позволила достаточно просто реализовать Basic HTTP Auth. В последвии добавил возможность задействования шаблонизатора Jinja2.
* [Проект на Django](https://github.com/BorisPlus/otus_webpython_006) - переработан проект на Flask. Задействуется Django Class Based Views, фишка - свой Django Widget [admin_img_widget](https://github.com/BorisPlus/otus_webpython_006/blob/master/README.files/images/screenshots/admin_img_widget.png) и "свои" декораторы для полей в админ-панели. Обосновано и расписано все. Также заполняется тестовыми данными с сайта МВидео. П.С. О возможности создания Django-Management комманд я тогда не ведал.
* [Django ORM](https://github.com/BorisPlus/otus_webpython_016) - материал о том, как можно (и НУЖНО) влиять на генерируемые Django SQL-запросы к базам данных с целью снижения нагрузок. 
* [Основы динамичного Frontend](https://github.com/BorisPlus/otus_webpython_013) - CSS, JS, шрифты (ох уж эта буква "Ё" на устройствах Мак).
* [Frontend непосредственно в Django](https://github.com/BorisPlus/otus_webpython_007_008) - проект портала обучения на струнных щипковых музыкальных инструментах. CSS для разных устройств (десктоп \ мобильные), взаимодействие по REST API, боковая панель мониторинга и отладки, Class Based Configs (обожаю гибкость). Демонстрируется Django-админка и гостевой публичный доступ.
* Пример того, как организовать взамодействие [Frontend](https://github.com/BorisPlus/otus_webpython_019_frontend) и [Backend](https://github.com/BorisPlus/otus_webpython_019_backend). 
* В рамках блока домашних работ по Frontend был сделан проект для подключения модераторами на своих сайтах формы информирования пользователем о наличии опечаток - [BugReport](https://github.com/BorisPlus/BugReport).
* [Webpack](https://github.com/BorisPlus/otus_webpython_018) - как собрать весь-весь JS в один проект. 
* [Проект с Redis](https://github.com/BorisPlus/otus_webpython_020_021) - многоочерЁдная обработка задач с Redis Queue на примере проверки активности Интернет-ресурсов и сервисов. 
* [Проект Django с Сelery](https://github.com/BorisPlus/otus_webpython_020_021_celery) - пример запуска в Django асинхронной триггер-задачи (по отработке действия во view) с использованием Сelery на стороне сервера (это не AJAX на стороне пользователя). 
* [Проект React](https://github.com/BorisPlus/otus_webpython_023) - основы основ NPM и React
* [Пример взаимодействия пользовательского React с серверным Django](https://github.com/BorisPlus/otus_webpython_025) - форма с чатом.
* Промежуточный вариант курсовой работы: [Django ⇄ (Redux & React \ Vue)](https://github.com/BorisPlus/otus_webpython_027) и пример упаковки в Докер.

## Курсовой проект

* [Django ⇄ (Redux & React)](https://github.com/BorisPlus/otus_webpython_030) - форма с чатом, авторизация посредством Django, взаимодействие Django сервера и (Redux & React) происходит по REST API с использованием JWT и многим другим, что было ранее описано. 


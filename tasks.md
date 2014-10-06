# TASKS #
https://github.com/a-x-/my-tasks-and-triggers/blob/master/tasks.md

## Развитие  (книги)
* как завоевывать друзей и влиять на людей (Дейл Карнеги) — Начал чтение
    - Говорить о том, что волнует собеседника
    - Улыбаться
    - Помнить имена и называть по имени
    - Слушать
* Отто Крегер, Дженет Тьюсон "Типы людей: 16 типов личности, определяющих, как мы живём, работаем и любим"
    
    > Данная книга поможет понять причины поступков других людей и разобраться в мотивах своего поведения — на работе, в любви, в воспитании детей и иных сферах повседневной жизни. Представленный вариант юнговской типологии — типоведение Майерс-Бриггс — родственен популярной в России соционике.
* Психология жестов
* Чалдини психология влияния http://royallib.ru/book/chaldini_robert/psihologiya_vliyaniya.html
* Системное мышление, диалектика, ведение споров (триз)
    - https://ru.wikipedia.org/wiki/Логическая_ошибка
* память (запомнить все) 
    * http://blog.mann-ivanov-ferber.ru/2014/04/06/nash-avtor-v-knige-rekordov-rossii/ — «Помнить все»
* теория категорий, функциональное программирование, матроиды, моноиды (хаскел)
* английский язык (грамматика, речь)
* (Психбольница в руках пациентов), (Как пасти котов)
* http://bakhirev.biz/book/#nzZQP — Сюрреализм на JavaScript


## SEO
* # TT-Psy. See [TT-Psy.md](/TT-Psy.md)

## ab-store
Tasks: http://bb.damina.org/ab-store

##damina.company
Tasks: http://bb.damina.org/ds

## web-dev
See http://bb.damina.org/ngin2/issues


## Быт
* ~~[Найти стул](http://www.avito.ru/moskva/mebel_i_interer/kompyuternye_stoly_i_kresla?metro=29-103-2142&q=кресло&s=1)~~.
* ~~Привезти стул~~
* [Получить карту Авангарда](https://www.avangard.ru/ccorder/faces/step2.jspx).
* Посмотреть ролики ~~ролик Алёны~~, ~~ролик про осознанный сон~~, про школу.
* Подарить маме домен `mekhonoshina.ru`
* Купить `mekhonoshin.ru`

## Lenovo
* Купить RAM (1600, 1.5, 11)
    - http://www.ulmart.ru/goods/782653 — 2ГБ
    - http://www.ulmart.ru/goods/630505 — 4ГБ
* Поставить OS X 10.9

## os x
* ~~Установить на VirtualBox~~. -- ok
* ~~увеличить диск os x.~~ -- cancel (видимо не выйдет).
* подключить офис к маку.
* 1) Проверить ставибильность OS X на мой ноут.
	- изъять ssd и hdd
	- поставить чистый hdd
	- подключить dvd-привод.
	- записать iso (тот же самый образ os x от Hazard'а) на болванку.
	- попытаться установить OS X.
* 2) Окончательно Поставить OS X на ноут. -- СБ, ВС.
	- за dd'ать w7 в резервный файл.
	- удалить разделы с ssd предварительно скопировав некиторые файлы.
	- отключить hdd, подключить dvd-привод.
	- записать iso (тот же самый образ os x от Hazard'а) на болванку.
	- попытаться установить OS X.


## Инструменты
* Github like low RAM/CPU (min: RPi) https://github.com/gogits/gogs
* BaseCamp — Basecamp makes it easy for people in different roles with different responsibilities to communicate and work together.
  Может решить «проблему Игоря и bitbucket'а»

## Развитие Web-dev 

### General web-programming

* Разобраться с внедрением зависимостей. Тестированием. Непрерывной интеграцией.
* Контейнеризацией (docker). Core OS.

### Backend

SSL

Внедрить SSL

OpenSSL changes in PHP 5.6.x  http://ru2.php.net/manual/ru/migration56.openssl.php

##### PHP
###### Нужно обозреть php фреймворки: codeigniter > kohana > yii > laravel (Symfony2?)
http://vschart.com/compare/laravel/vs/yii -- сравнение laravel — yii.
http://wiki4tech.ru/Сравнение_PHP-фреймворков -- сравнение php фреймворков (+ссылки на другие сравнения).

###### PHP 5.6

Релиз!

Вычисляемые константы, ...-operator!

###### Поразбираться с composer.

###### Почитать про modern php и best-practicies.
* http://getjump.github.io/ru-php-the-right-way/ — php: правильный путь

##### Alternativies
###### Найти и обозреть фреймворки под Python, Node.js.
* Нужно понять, удовлетворяют ли эти решения моим представлениям или собственные идеи имеют право на жизнь.
* http://habrahabr.ru/post/116030/ — большое обсуждение Самописное решение или Фреймворк (в комментах).

### DevOps
Нужно так же решить, 

* как развивать деплоймент, 
* как строить админки, 
* как осуществлять миграции БД (видимо нужно отказаться от своей ORM «AlxMq», т.к. она делает миграции невозможными)
* и вообще как управлять конфигурацией.
* Рассмотреть Hg (aka ртутный, aka mercurial). Видимо он лучше работает с подмодулями чем Git. **TODO** выяснить это.
* Скаффолдинг (генерация заготовки проекта (англ. bootstrap))
    - http://frontender.info/skaffolding-dlya-frontenderov/ — Скаффолдинг (Yoman и всё все всё)
* Fail2ban  http://www.fail2ban.org/wiki/index.php/Main_Page
  > Fail2ban scans log files (e.g. /var/log/apache/error_log) and bans IPs that show the malicious signs -- too many password failures, seeking for exploits, etc. Generally Fail2Ban is then used to update firewall rules to reject the IP addresses for a specified amount of time, although any arbitrary other action (e.g. sending an email) could also be configured. Out of the box Fail2Ban comes with filters for various services (apache, courier, ssh, etc). 
  >Fail2Ban is able to reduce the rate of incorrect authentications attempts however it cannot eliminate the risk that weak authentication presents. Configure services to use only two factor or public/private authentication mechanisms if you really want to protect services. 



### Frontend
Поразбираться с
* Angular
* lo-dash
* js es5
* js es6 (вместо require.js).

Менеджеры пакетов. Поразбираться с bower.
Планировщики. Поразбираться с gulp (вместо Grunt).

### CMS
#### WP
wp-cli

http://tmoitie.uk/2014/08/a-modern-composer-workflow-with-wordpress/

#### No WP
Кроме того, нужно посмотреть, какие есть альтернативы WordPress

* Craft


# Что можно посмотреть и почитать просто для развлечения

* Inception — http://www.kinopoisk.ru/film/447301/
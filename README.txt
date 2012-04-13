=== uLogin - виджет авторизации через социальные сети ===
Donate link: http://ulogin.ru/
Tags: ulogin, login, social, authorization
Requires at least: 1.0
Tested up to: 1.1
Stable widget tag: 1.7
License: GPL3

Форма авторизации uLogin через социальные сети. Улучшенный аналог loginza.

== Description ==

uLogin — это инструмент, который позволяет пользователям получить единый доступ к различным Интернет-сервисам без необходимости повторной регистрации,
а владельцам сайтов — получить дополнительный приток клиентов из социальных сетей и популярных порталов (Google, Яндекс, Mail.ru, ВКонтакте, Facebook и др.)

== Installation ==
1. Скопируйте содержимое в директорию с yii приложением (по умолчанию protected)
2. Виджет авторизации вставляется следующим кодом:

<?php  $this->widget('application.components.UloginWidget', array(
    'params'=>array(
        'redirect'=>'http://'.$_SERVER['HTTP_HOST'].'/index.php?r=ulogin/login' //Адрес, на который ulogin будет редиректить браузер клиента. Он должен соответствовать контроллеру ulogin и действию login
    )
)); ?>

== Frequently Asked Questions ==

= Нужно ли где-то регистрироваться, чтобы плагин заработал? =

Нет, плагин заработает сразу после установки!

== Screenshots ==


# final-autotests-labirint
# В данном репозитории представлено ряд автотестов для интернет-магазина лабиринт https://www.labirint.ru/ с помощью 
Python и фреймворка Selenium. Для запусков тестов необходимо установить фреймворк selenium(pytest-selenium) 

В рамках данного проекта автоматизированы основные сценарии пользователей:
* авторизация на сайте
* поиск автора
* поиск книги по названию
* поиск книги по ISBN
* добавление книги в Отложенные
* добавление книги в Корзину
* оформление покупки
* отправки вопроса в поддержку
* проверена работоспособность части ссылок на главной странице

How to run:

Download driver for Chrome: https://chromedriver.chromium.org/downloads

Install all required python packages library

Run in terminal with line: python -m pytest -v --driver Chrome --driver-path <~>/chromedriver.exe tests/"enter the name of the file with autotests".py

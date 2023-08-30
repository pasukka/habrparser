# Программа для парсинга Habr

✔ Python

✔  Requests

✔  BeautifulSoup

✔ Компьютерная лингвистика

## Описание задачи
Была поставлена задача составления корпуса текстов, относящихся к направлению компьютеной лингвистики. Для составления была написана программа для парсинга сайта habr.com, содержащего статьи разнообразных направлений, связанных с программированием.

В примере представленном в main.py используется список хабов статей, относящихся к интересующей нас области:
1.   Natural Language Processing;
2.   Artificial Intelligence;
3.   Искусственный интеллект';
4.   Data Mining + (Machine learning / Машинное обучение);
5.   Big Data + (Machine learning / Машинное обучение / Семантика);
6.   Поисковые технологии + (Data Mining / Machine learning / Машинное обучение / Big Data).

## Описание работы программы

На вход программе подается номер страницы, после чег происходит сравнение хабов со страницы с ключевыми хабами из составленного списка. Если статья удовлетворяет условию, то она сохраняется в формате html и/или txt в указанную(-ые) папку(-и).

## Как пользоваться программой

Перед использованием необходимо убедиться, что установлен модуль Requests. Если нет, то воспользуйтесь командой:

``` pip install requests ```

## Ссылка на оригинальный файл
    https://colab.research.google.com/drive/13S76mhPxaaNy_IgnJU--CnQRgW6n5Ueo
# Лабораторная работа Виктора Решетова №1: Bash-скрипт

Написать shell-скрипт, выполняющий простые операции работы с командной строкой.

## Короткая справка
Если необходимо получить результат выполнения функции, выражение оборачивается в такую конструкцию:
$(expression)
echo выводит на печать (по умолчанию на экран) всё, что передано ему в качестве аргумента
Если встречаются служебные символы, которые надо передать аргументом, они экранируются обратным слэшом

## Общие требования
* Скрипт должен быть сохранён в текстовый файл с расширением .sh

* Первая строка скрипта: #!/bin/bash (указывает на используемый интерпретатор)

* Скрипт должен быть сохранён в Git репозитории и отправлен на проверку

* Все правки (если они будут) должны быть отражены в версионировании в том же репозитории

* Файл с результатами выполнения скрипта должен лежать рядом со скриптом


## Задача 3
Создать в текущей директории текстовый файл с содержимым переменной окружения $PATH и с помощью скрипта ограничить права на чтение и запись только для владельца, запуск запретить всем.

![alt text](https://pbs.twimg.com/media/Eh3lZduX0AA7ssv.jpg)

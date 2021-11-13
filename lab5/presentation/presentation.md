---
## Front matter
lang: ru-RU
title: "Лабораторная работа №5"
subtitle: "Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов"
author: "Калинина Кристина Сергеевна"

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

## Выполнение

 1. Выполнение лабораторной работы
 
 2. Оформление отчета и презентации
 
 3. Выгрузка видео на youtube и файлов на GitHub
 
## Работа с simpleid.c

![Код программы simpleid.c](image/2.jpg){ #fig:002 width=70% }

## Работа с simpleid.c
 
![Выполнение программы и сравнение результата с выводом команды id](image/3.jpg){ #fig:003 width=70% }

## Работа с simpleid2.c

![Код программы simpleid2.c](image/4.jpg){ #fig:004 width=70% }

## Работа с simpleid2.c
 
![Выполнение программы simpleid2.c](image/5.jpg){ #fig:005 width=70% }

## Смена атрибутов и владельца файла simpleid2

![Смена владельца и установка атрибутов](image/6.jpg){ #fig:006 width=70% }

![Проверка и запуск программы](image/7.jpg){ #fig:007 width=70% }

## Повтор действий относительно SetGID-бита

![Установка атрибутов](image/8.jpg){ #fig:008 width=70% }

![Повтор действий с SetGID-битом](image/9.jpg){ #fig:009 width=70% }

## Создание readfile.c

![Код программы readfile.c](image/10.jpg){ #fig:010 width=70% }

## Компиляция readfile.c

![Компиляция программы readfile.c](image/11.jpg){ #fig:011 width=70% }

## Смена прав и владельца файла readfile.c

![Смена владельца файла readfile.c и прав на него](image/12.jpg){ #fig:012 width=70% }

![Отказ в чтении readfile.c](image/13.jpg){ #fig:013 width=70% }

## Смена прав и владельца файла readfile

![Смена владельца файла readfile и установка SetU’D-бит](image/14.jpg){ #fig:014 width=70% }

## Чтение readfile.c и "/etc/shadow"

![Чтение readfile.c и "/etc/shadow"](image/15.jpg){ #fig:015 width=70% }

## Работа с атрибутом Sticky

![атрибут Sticky на директории /tmp](image/16.jpg){ #fig:016 width=70% }
 
![Создание file01.txt и смена атрибутов](image/17.jpg){ #fig:017 width=70% }

## Работа с файлом от пользователя guest2

![Работа с file01.txt от guest2](image/18.jpg){ #fig:018 width=70% }
 
![Снятие атрибута Sticky с директории /tmp](image/19.jpg){ #fig:019 width=70% }

## Работа с файлом от пользователя guest2
 
![Повторное выполнение команд от guest2](image/20.jpg){ #fig:020 width=70% }
 
![Возвращение атрибута Sticky на директорию /tmp](image/21.jpg){ #fig:021 width=70% }

## Выводы

Таким образом я успешно приобрела изучила механизмы изменения идентификаторов, применения SetUID- и Sticky-битов. Получила практические навыки работы в консоли с дополнительными атрибутами. Рассмотрела работу механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

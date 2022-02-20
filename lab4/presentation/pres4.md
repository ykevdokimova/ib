---
## Front matter
lang: ru-RU
title: Отчет по лабораторной работе №4
author: |
	 Евдокимова Юлия НПИбд-01-18\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: Информационная Безопасность--2022, 19 февраля, 2022, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
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

# Цели и задачи работы

## Цель лабораторной работы

Получить практические навыки работы в консоли с расширенными атрибутами файлов.

## Задание к лабораторной работе

Лабораторная работа подразумевает выполнение последовательно необходимых действий, чтобы получить навыки работы в консоли с расширенными атрибутами файлов. 

# Процесс выполнения лабораторной работы

## Процесс выполнения

1. От имени пользователя guest определила расширенные атрибуты файла, установила  на file1 права, разрешающие чтение и запись для владельца файла. Попробовала установить на file1 расширенный атрибут "a" от имени пользователя guest, но получила отказ.

2. Попробовала установить расширенный атрибут "a" на файл /home/guest/dir1/file1 от рута.

3. От пользователя guest проверила правильность установления атрибута. Выполнила дозапись в файл file1 слова «test». 

4. Прочитала file1 командой cat и убедилась, что слово test записалось. Попробовала удалить файл file1, стереть имеющуюся в нем информацию, установить на файл file1 права, запрещающие чтение и запись для владельца файла. Все эти команды выполнить не удалось, кроме дозаписи и чтения файла.

5. Сняла расширенный атрибут "a" с file1 от имени рута.

6. Повторила операции, которые ранее не удавалось выполнить. После снятия атрибута "а" мы можем выполнять все действия.

7. Установила расширенный атрибут "i" на file1 от имени рута.

7. Повторила операции. С установленным атрибутом "i"  нам не удалось выполнить ни одного действия.  


# Выводы по лабораторной работе

## Вывод

На основе проделанной работы получила практические навыки работы в консоли с расширенными атрибутами файлов.
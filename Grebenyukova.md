# Инструкция по работе с Git

## Базовые команды с первого семинара

* *git unit* - команда, инициализирующая создание репозитария
* *git add* - команда, добавляющая файл в отслеживание
* *git commit -a -m "Текст коммита" - команда фиксирующая изменения файла и комментарий этого изменения.
* *git status* - команда показывает состояние файлов: какие файлы изменены, но не добавлены, какие ожидают коммита.
* *git diff* - команда показывающая, что конкретно поменялось, а не только какие файлы были изменены - показывает вам непосредственно добавленные и удалённые строки.
* *git log* - команда перечисляет коммиты, сделанные в репозитории в обратном к хронологическому порядке, т.е. просмотр истории коммитов.

## Базовые команды со второго семинара

* *git branch* - команда, отображающая в терминале список существующих веток;
* *git branch branch-name* - команда, создающая ветку с именем *branch-name*;
* *git merge name_branch* - используется для слияния одной или нескольких веток в текущую;
* *git checkout* - используется для переключения веток и выгрузки их содержимого в рабочую директорию.


## Базовые команды с третьего семинара

* *git clone* - команда позволяет склонировать внешний репозиторий на наш ПК;
* *git pull* - команда позволяет скачать все из текущего репозитория и автоматически сделать "merge" с нашей версией;
* *git push* - команда позволяет отправить нашу версию репозитория на внешний репозиторий.

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*)  или знаком нижнего подчеркивания(_). Например, *вот так* или _вот так_

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, это чашки!](caps.jpg)
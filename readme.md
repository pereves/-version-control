# Первый запуск git
## *1. Создаем локальный репозиторий*

>git init
***

## *2. Делаем файл отслеживаемым*

>git add readme.md

>git add.
***

## *3. Создаем изменение*

>git commit -m "Первый коммит"
***

## *4. Указать пользователя и почту*

>git config --global user.email "you@example.com"

>git config --global user.name "Your Name"
***

## *5. Проверить статус файла*

>git status
***

## *6. История изменений*

>git log

>git log --oneline
***

## *7. Посмотреть разницу после изменений*

>git dif
***

## *8. Переключаться между изменениями*

>git checkout
***

## *9. Создать ссылку*

>[Изображение](i.webp)
***

## *10. Вывести изображение*

>![Изображение](i.webp)
***

# Работа с ветками

## *1. Выводим список веток в репозитории*

>git branch

***

## *2. Создаем новую ветку с именем new_branch*

>git branch new_branch

***

## *3. Удаляем ветку с именем new_branch*

>git branch -d new_branch

***

## *4. Переходим на ветку с именем new_branch*

>git checkout new_branch

***

## *5. Выводим список изменений в виде графа/дерева*

>git log --graph

***

## *6. Сливает ветку branch_name с текущей меткой*

>git merge branch_name

***

# Работа с удаленным репозиторием

## *1. Склонировать внешний репозиторий на ПК*

>git clone

***

## *2. Скачать все из текущего репозитория и объединить с текущей версией*

>git pull

***

## *3. Отправить текущую версию репозитория на внешний репозиторий*

>git push

***
## *4. Сделать файл или папку неотслеживаемыми*

>.gitignore внутри указать имя файла или папки

***
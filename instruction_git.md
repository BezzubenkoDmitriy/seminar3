# **Инструкция по вводу в контроль версий программы git**

## Что такое git

git это программа

## Инициализация репозитроия 

Чтобы инициализировать (создать) новый репозиторий нужно ввести в терминале команду: 

    git init

## Проверка репозитория

Чтобы проверить состояние репозитория необходимо ввести команду:

    git status

## Добавление изменений

Чтобы добавить изменения для сдледующего индекса необходимо ввести команду:

    git add <filename>

## Фиксация или сохранения

Чтобы зафиксировать и сохранить добавления во внутренней базе данных необходимо ввести команду

    git commit


## Описание commita

Чтобы  описать добавленные изменения ,необходимо ввести команду:

    git commit -m"  "


## Добавление изменений

Так же можно внести изменения для следующего индекса с помощью команды:

    git commit -a

 ## Добавить и сохранить

 Можно внести изменения и сразуже зафиксировать данные с помощью одной команды:

    git commit -a -m"  "


## Журнал изменений

Перед переключением версии файла в git используйте команду:

    git log

  ## Журнал изменений (сокращенный)  

  Журнал показывает не полное название commita с помощью команды:

    git log --oneline


## Просмотр истории

Для просмотра истории commita по всем веткам используют команду

    git log --all


## Просмотр истории

Переключаться между историями можно командой

    git log --all


## Просмотр истории(сокращенный)

Просмотр всей истории

    git log --oneline --all


## Сравнение 

Чтобы посмотреть разницу между текущем файлои и сохранённым нужно ввести команду:

    git diff

## Переключения между версиями

Переключение между версиями происходит с помощью ввода :

    git checkout \<hash>

    
![отпуск](sea.jpg)


## Ветвление

Ветки в git нужны для легкой работы с черновиками и чистовиками

## Создание новой ветки

Чтобы создать новую ветку,необходимо ввести команду:

    git branch name

## Переход между ветками

Чтобы перйти на другую ветку

После создания новой ветки ,для отображения графического ответвления ,необходимо создать новый commit в ветке master

## Слияние
## Слияние

Слияние выполняется с помощью команды:

    git merge
    

Чтобы влить изменения из одной ветки в другую

### Конфликты слияния

Если при слияние в двух версиях файла одна строка напечатана по- разному, то Git сообщит о конфликте и предложит выбрать ,какие изменения записать.


## Удалить ветку 

можно с помощью команды:

    git branch -d name branch

   
 ![фото](sabor.jpg)

 ## Чтобы выделить полужирным и курсивом 

 нужно выделить текст __*вот так*__



## Визуализация веток


ключ -graph в связке с командой log позволяет отобразить коммиты в виде дерева


так же можно

    git log --oneline --all --graph
    

А тут я создам просто конфлик 


## Удаленные репозитории

Удаленные репозитории это Очень полезная штука






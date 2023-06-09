# Инструкция по работе с Git и MarkDown

## Основные команды Git-а

* git init – инициализация локального репозитория

* git status – получить информацию от git о его текущем состоянии

* git add <file's name> – добавить файл или файлы к следующему коммиту

* git add . - добавить все файлы в папке

* git commit -m “message” – создание коммита

* git log – вывод на экран истории всех коммитов с их хеш-кодами

* git log graph - вывод на экран истории всех коммитов с их хеш-кодами в ином виде

* git checkout – переход от одного коммита к другому

* git checkout main – вернуться к основной ветке

* git checkout <branch's name> - перейти к работе с определенной веткой

* git diff – увидеть разницу между текущим файлом и закоммиченным файлом

* git branch - вывести имеющиеся ветки

* git merge <2nd branche's name> - слияние нескольких веток

### Команды Git из второго семинара

* git branch branch_name - создание новой ветки

* git branch -d branch_name - удалить ветку

* git log —oneline - кратий журнал

* вместо git add <file’s name>, а затем git commit -m “message”
можно git commit -am “message”

* git checkout -b branch_name - позволяет создать новую ветку и сразу автоматичнски на нее переключается

* git clone - скопировать удаленный репозиторий на локальный

* git pull - перенести обновленные данные с удаленного на локальный репозиторий
* git push - добавить изменения на удаленный репозиторий


# Инструкция для работы с MarkDown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочкой (*) или знаком нижнее подчеркивание (_). Например, *вот так*.

Чтобы выделить текст полужирным, нужно обрамить его двойными звездочками или двойными знаками нижнего подчеркивания. Например, **вот так**.

Альтернативные способы выделения текста нужны для совмещения обоих этих способов. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

Чтобы сделать текст зачеркнутым, нужно обрамить его такими знаками (~/~​). Например, ~~​вот так~~.​

## Работа с изображениями

 Чтобы вставить изображения в текст, достаточно написать следующее: 
 
 ![Картинка не открылась:(](%D0%BF%D0%B5%D1%81%D0%B8%D0%BA.jpeg)


## Списки

Чтобы добавить ненумерованные списки, нужно пометить элемент звездочкой или знаком плюс. Например, вот так:
* Первый пункт
* Второй пункт
+ Третий пункт 
+ Четвертый пункт
* Пятый пункт

Чтобы добавить нумернованные списки, нужно пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт 

## Ссылки

Чтобы сделать ссылку, нужно добавить квадратные скобки с названием ссылки (или ничего не добавлять), а затем круглые скобки с самой ссылкой. Вот так:

[Ссылка на сериал, который я сейчас смотрю и от которого я без ума.](https://hd.kinopoisk.ru/film/4d17dfdcc88dc78fb6b83473a47c98e0?from_block=kp-button-online) 


## Таблицы
 >Пробую еще раз
Для создания таблицы нужно использовать вертикальные линии (|) и тире (-). В первой строке таблицы мы строим заголовок, разделяя эту строку тремя или более дефисами (---). Ширина ячеек может быть любой. Например:

| Заголовок  | Заголовок   |
| --- | --- |
| Текст   | Текст    |
| Текст    | Текст    |

## Цитаты

Чтобы сделать цитату, необходимо поставить знак больше (>) в начале предложения. Вот так:

> Привет
> Как дела?

## Горизонтальные линии (разделители)

Для того чтобы создать горизонтальную линию, необходимо поместить три (или более) дефиса (-) или звездочки (*) на отдельной строке текста. Между ними возможно располагать пробелы. Например, вот так:

Первая часть текста, который необходимо разделить
***
Вторая часть текста, который необходимо разделить

Или

Первая часть текста, который необходимо разделить

---

Вторая часть текста, который необходимо разделить

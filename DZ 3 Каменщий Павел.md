# Инструкция по разметке в Markdown.

>Здравствуйте. Для начала поговорим о том как редоктировать такст с помощью языка Markdown.

Для того что бы Создать большой заголовой необходимо поставить один знак #. 
Что бы сделать заголовок меньшего размера чем основной поставте два знака ##.

## Выделение текста

Для токо что бы написанный текст был с курсивом необходимо перед и после слова поставить один знак *.

 *Курсив*

 Для получения жироного шрифта необходмио поставить по два знака * в начале и конце слова или предложения.

**полужирным или жирный**

Также есть вспомогательные обозначения например (_) это нужно елси вым необходимо сделать курсивы жирными.

Например: *Величайшие преступления совершаются из за стремления к __избытку__, а не к предметам __первой необходимости__*.

Таким образом если необходимо сделать слоко и курсиво и полужирным то так это сделать возможно.

## Списки

Также можно создать списки нескольких видов: нумированный и не нумерованный (точечный). 
Что бы создать нумерованный список просто поставте номер и точку. 
Для создания не нумерованного просто поставте знак * и пробел в начале предложения.

* элемент не нумерованный
* элемент не нумерованный
* элемент не нумерованный

1. элемент нуменованный
2. элемент нуменованный
3. элемент нуменованный

## Цитаты

Для цитирования в языке Markdown используется знак «больше» («>»). 
Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой абзаца.

>Цитата первого уровня
>>Второго уровня и т.д.

## Ссылки

Также можно вставлять гиперссылки.

https://gist.github.com/Jekins/2bf2d0638163f1294637

# Работа в программе Git

*Тепарь рассмотрим как начать работу в Git, а также какие команды есть на этой пратформе.*

### Начало работы.

>После установки Git необходимо прописать несколько команд для присвоения вашего имени и почты.

* git config --global user.name «Ваше имя англ буквами»
* git config --global user.email ваша_почта@example.com

Это упростит комендную работу когда вам необходимо передать или показать ваши нароботки.

### Оснавные команды

* git add
 >Команда git add добавляет содержимое рабочего каталога в индекс.
 * git status
 >Команда git status показывает состояния файлов в рабочем каталоге и индексе.
 * git diff
 >Команда git diff используется для вычисления разницы между любыми двумя Git деревьями.
 * git commit
 >Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных.
 * git clean
 >Команда git clean используется для удаления мусора из рабочего каталога.

### Порядок написаноя команд что бы ...
#### Удалить ветки.
>git branch -d название ветки 
### Что бы посмотреть как велась работа с ветками.
Введите команду 
>git log --graph
### Совместить две ветки.
> git merge незвание ветки.
### Очистить терминал.
clear
## Команды для работы с удаленным репозиториями.
*Для начала необходимо связать свой GIT с сервисом GitHub.*

После этого можно работать с репозиториями не только на вашем ПК но и с репозиториями других пользователей GitHub, которые дали такую возмодность.

### Команды для скачки репозитьриев с GitHub.

git clone 
> Эта команда нужна для "клонирования" репозитория с сайта на ваш ПК

**Пример**
>git clone h_ttps://github.com/название репозитория который вы хотите скачать.

После этого в вашу папку скопируется все данные этого репозитория. 
Таке эта команда пытается слить все ветки на локальном ПК и в удаленном репозитории.

### Команда для придложения изменений.

Представим что вы сказали чей-то проэкт и хотате предложить своё решение.

pull request
>Эта команда поможет вам с этим. Она отвечает за предложения изменения создателю репозитория.

После того как вы отпрвите запрос создатель репозитория может принять ваше изменения или нет.
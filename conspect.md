# Конспект по теме: Введение в контроль версий

## **Текунов Д.И.**

## **Git и его основы**


<image src=  https://fuzeservers.ru/wp-content/uploads/3/0/c/30c29ce4cc08523ecc6e1f205bc207d0.jpeg>



*Git- это распределенная система управления версиями.*

Чаще всего Git используется для контроля и отслеживания версий исходного кода. К примеру, для отката на более раннюю версию, для исправления ошибок или уточнения информации. Также, Git используется многими программистами для упрощённой командной работы, при которой сразу все члены команды смогут увидеть изменения, вносящиеся в код.

**Git может быть ипользован как с помощью сторонних графических интерфейсов, так и с командной строкой*

## **Основные команды, используемые при работе с Git.**

* git --version- выводит версию Git. С помощью этой команды можно убедиться в том, что Git  в принципе установлен на компьютере и нормально работает.
* git init- подключает Git к текущему проекту.
* git reflog- выводит список сохранений.
* git add- добавляет файл.
* git branch- показывает список ветвей.
* git checkout- позволяет перемещаться между сохранениями или ветвями
* git status- текущее состояние ветви.
* git log- выводит все коммиты.
* git commit -m добавляет комментарий к коммиту.
* git commit -am добавляет комментарий + файл для создания коммита.
* git merge- соединяет ветки
* git log --graph- показывает графически все изменения между ветвями и т.д.
* git checkout -b название ветки- создаёт ветку и сразу перемещает на неё
* git remote add origin ссылка- добавляет удалённый репозиторий в GitHub
* git branch -M main- переименовывает ветку для GitHub
* git push -u origin main- отправляет репозиторий main в GitHub
* git pull- подтягивает изменения, которые были внесены на GitHub
* git clone ссылка- позволяет создать копию файла с GitHub

## **Ветки** 

Для создания ветки нужно написать следующий код: git branch название ветки

Чтобы перейти на созданную ветку нужно прописать в терминале git checkout название ветки

Для совмещения веток нужно перейти на основную ветку и в терминале прописать git merge название ветки с которой совмещаем

Для удаления ненужной ветки нужно прописать команду git branch -D название ветки

Ветки создаются по разным причинам- в некоторых случаях для использования их в качестве черновиков, в некоторых - для совместной работы.

## **Картинки**

Чтобы вставить изображение в текст, достаточно написать следующее: (![Текст к фото](название файла)). Изображение должно находиться в папке репозитория.

Либо, <image src=>

## **Выделение текста**

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*). Например, *Вот так*. Также, можно воспользоваться знаком подчёркивания (_) перед текстом. Полужирный текст можно сделать с помощью двойного знака подчёркивания (__).

Чтобы выделить текст полужирным, необходимо выделить его двойными звёздочками (**). **Вот так**.

## **Списки**

Чтобы добавить ненумерованные списки необходимо выделить пункты звёздочкой (*).
Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3

Чтобы добавить нумерованные списки, необходимо пронумеровать пункты (1. 2. 3.)

Например, вот так:

1. Первый пункт
2. Второй пункт
3. Третий пункт
  
## Алгоритм создания pull request

  1. Делаем fork репозитория
  2. Делаем clone 
  3. Создаём новую ветку и внеё вносим изменения
  4. Делаем коммиты 
  5. Отправляем свою версию в свой GitHub
  6. На сайте GitHub нажимаем на кнопку pull request
  


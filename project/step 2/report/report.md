---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Этап 2"
author: "Полина Витальевна Барабаш"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данного этапа работы является размещение на Github pages данных о себе, сделать два поста [@tuis].


# Выполнение работы

**Задание 1.** Разместить фотографию владельца сайта. Разместить краткое описание владельца сайта (Biography). Добавить информацию об интересах (Interests). Добавить информацию от образовании (Education).

Для того, чтобы добавить информацию о себе, я перешла в репозитории сайта в каталог content, затем в authors и наконец в admin, где находится файл index.md и avatar.jpg (рис. [-@fig:001]).

![Местонахождение файлов для ввода информации о владельце сайта](image/fig001.png){#fig:001 width=70%}

Сначала я удалила изначальную фотографию, хранящуюся в avatar.jpg и добавила свою фотографию в файл с таким же названием (рис. [-@fig:002]).

![Моя фотография в файле avatar.jpg](image/fig002.png){#fig:002 width=70%}

Затем я вошла в режим редактирования файла index.md (рис. [-@fig:003]).

![Файл index.md в режиме редактирования](image/fig003.png){#fig:003 width=70%}

И разместила всю необходмую информацию о себе, которую можно теперь видеть на сайте (рис. [-@fig:004]).

![Вся заполненная информация о себе](image/fig004.png){#fig:004 width=70%}

**Задание 2.** Написать пост по прошедшей неделе.

Для удобства я скопировала свой репозиторий на гитхаб на свой локальный компьютер и создала каталог week410, в которой создала файл index.md и добавила картинки, которые планировала использовать в посте (рис. [-@fig:005]).

![Каталог с материалами для поста](image/fig005.png){#fig:005 width=70%}

Я изучила рекомендации по написанию поста по прошедшей неделе [@shablon]. И принялась писать пост.

Так как текст пишется в формате маркдаун, то для написания поста мне пригодились знания о разметке, полученные в течении прошлого и этого семестров. 

Я написала пост и с помощью команд git add ., git commit ... и git push обновила удаленный репозиторий.

После этого на сайте появился новый пост (рис. [-@fig:006]).

![Пост по прошедшей неделе на сайте](image/fig006.png){#fig:006 width=70%}

**Задание 3.** Написать поста по выбранной теме.

Я выбрала тему Управление версиями. Git. Я изучила различный материал, больше всего опираясь на книгу с сайта Git [@git]. Затем подготовила и нашла нужные картинки. Разместила их в нужной папке и опять же написала код в index.md нужной папки. Так как я делала этот пост прямо в репозитории на github, мне не нужно было ничего выгружать, только закончив изменения, сохранить их в главной ветке. И пост на сайте появился (рис. [-@fig:007]).

![Пост по выбранной теме на сайте](image/fig007.png){#fig:007 width=70%}



# Выводы

При выполнении данного этапа индивидуального проекта я приобрела практические навыки заполнения главной страницы с информацией о себе и навыки написания постов на сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::





---
## Front matter
title: "Отчет по третьему этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Ардеев Никита Евгеньевич"

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

## Цель работы

Добавить к сайту достижения

# Задание


    Список достижений.
        Добавить информацию о навыках (Skills).
        Добавить информацию об опыте (Experience).
        Добавить информацию о достижениях (Accomplishments).
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Легковесные языки разметки.
        Языки разметки. LaTeX.
        Язык разметки Markdown.




# Выполнение проекта

Перехожу в директорию ~/work/blog/content, открываю файл _index.md, в нем будет осуществляться дальшейшая работа (рис. @fig:001)

![Путь, по которому работаем](image/1.png){#fig:001 width=70%}

В блоке features, там, где заголовок Skills прописал навыки. (рис. @fig:002)

![Добавление навыков](image/2.png){#fig:002 width=70%}

Далее добавил свой опыт в блоке Experience (рис. @fig:003)

![Добавление опыта](image/3.png){#fig:003 width=70%}

Чтобы поменять иконки, я скачал изображения формата .svg и поместил их в директорию ~work/blog/assets/media/icons/brands (рис. @fig:004)

![Добавление иконок](image/4.png){#fig:004 width=70%}

Далее в Accomplishments добавил достижения (рис. @fig:005)

![Добавление достижений](image/5.png){#fig:005 width=70%}

Добавил пост на тему по выбору (LaTex) в папке posts (рис. @fig:006)

![Добавление поста на тему по выбору](image/6.png){#fig:006 width=70%}

Добавил пост по прошедшей неделе в папке posts (рис. @fig:007)

![Добавление поста по прошедшей неделе](image/7.png){#fig:007 width=70%}

Проверяю, что все сделано корректно (рис. @fig:008)

![Результат выполнения работы](image/8.png){#fig:008 width=70%}

# Выводы

Добавил свои достижения.

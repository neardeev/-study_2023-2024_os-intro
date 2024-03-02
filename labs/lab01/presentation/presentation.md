---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Ардеев Н. Е.
institute:
  - Российский университет дружбы народов, Москва, Россия

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---


# Вводная часть

## Объект и предмет исследования

- Виртуальная машина
- OS Linux

## Цели и задачи

- Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Ход работы

## Установим виртуальную машину и загрузим в нее OS Linux

![-](image/hiop.png){#fig:001 width=60%}

## Подключим обновления и установим их

![-](image/Снимок экрана от 2024-02-11 14-33-49.png){#fig:002 width=60%}

## Подключим tmux и отключим SElinux

![tmux](image/Снимок экрана от 2024-02-11 14-58-48.png){#fig:003 width=30%}

![отключение SELinux](image/Снимок экрана от 2024-02-11 15-12-53.png){#fig:004 width=30%}

## Настроим раскладку клавиатуры

![-](image/Снимок экрана от 2024-02-11 16-29-11.png){#fig:005 width=60%}

## Подключим образ диска для хостовой ОС

![ионтирование диска](image/Снимок экрана от 2024-02-11 16-02-23.png){#fig:006 width=60%}

## Установим pandoc и LaTex

![texlive](image/Скриншот от 2024-02-11_18-18-19.png){#fig:007 width=35%}

![pandoc](image/Снимок экрана от 2024-02-11_16-43-49.png){#fig:008 width=35%}

# Результаты

## Вывод

 -Успешно установили Linux OS  на  ОВМ  и настроили его 

---
## Front matter
lang: ru-RU
title: Презентация лабораторной работы
subtitle: Лабораторная №4
author:
  - Барабаш П. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 08 марта 2024

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
 
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

---

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Барабаш Полина Витальевна
  * студентка 1 курса, НПИбд-01-23
  * Российский университет дружбы народов
  * [1132231841@pfur.ru](mailto:1132231841@pfur.ru)

:::
::: {.column width="30%"}

![](./image/я.png)

:::
::::::::::::::

## Цели и задачи

Цель: получить навыки правильной работы с репозиториями git.


Задачи:

- Загрузить и добавить необходимые программы
- Создать конфигурацию общепринятых коммитов
- Создание релизов и коммитов на github с помощью git-flow


# Анализ и результаты выполнения лабораторной работы


## Загрузка необходимых программ

![](./image/icons.png)


## Добавление commitizen и standard-changelog

![](./image/commitchangelog.png)


## Создание конфигурации общепринятых коммитов

- Конфигурация для пакетов Node.js:
  - инициализировать Node.js
  - добавить в файл package.json команду для формирования коммитов
  - отправить на github


## Создание конфигурации git-flow

![display:block;margin:auto|](./image/gitflow.png)



## Выводы

Мы научились работать с git-flow и выкладывать общепринятые коммиты



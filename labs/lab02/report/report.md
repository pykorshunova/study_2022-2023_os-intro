---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Система контроля версий git"
author: "Коршунова Полина Юрьевна"

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

Цель данной лабораторной работы состоит в изучении применения средств контроля версий и приобретении практических умений по работе с системой git. В ходе выполнения работы будет создан репозиторий, который можно найти по адресу https://github.com/pykorshunova/study_2022-2023_os-intro



# Выполнение лабораторной работы

1. Прежде чем создать репозиторий, необходимо настроить git: (рис. @fig:001).

![Настройка git](1.png){#fig:001 width=90%}

2. Создание ключей SSH и GPG (рис. @fig:002) (рис. @fig:003)

![Создание ssh](2.png){#fig:002 width=90%}

![Создание pgp](3.png){#fig:003 width=90%}

3. Настройка автоматических подписей git (рис. @fig:004)

![Настройка автоматических подписей git](4.png){#fig:004 width=90%}

4. Дальнейшая настройка репозитория (рис. @fig:005)

![Завершаем регистрацию](5.png){#fig:005 width=90%}

5. Клонирую созданный репозиторий (рис. @fig:006)

![Клонирую созданный репозиторий](6.png){#fig:006 width=90%}

6. Создаю неоходимые каталоги (рис. @fig:007)

![Создаю неоходимые каталоги](7.png){#fig:007 width=90%}

7. Отправляю файлы на сервер (рис. @fig:008)

![Отправляю файлы на сервер](8.png){#fig:008 width=90%}


#Ответы на контрольные вопросы


    Что такое системы контроля версий (VCS) и для решения каких задач они предназначаются?

Ответ: система, позволяющая работать нескольким людям над одним проектом.

    Объясните следующие понятия VCS и их отношения: хранилище, commit, история, рабочая копия.

Ответ: хранилище (репозиторий) - директория, хранящая конкретный проект; коммит - текущее состояние рабочей копии; история - последовательность коммитов в порядке, в котором они добавлялись в репозиторий; рабочая копия - текущее состояние репозитория, которое находится в состоянии изменения.

    Что представляют собой и чем отличаются централизованные и децентрализованные VCS? Приведите примеры VCS каждого вида.

Ответ: в централизованных VCS (Mercurial) все пользователи подключены к единому серверу; в децентрализованных VCS пользователи подключены к нескольким владельцам.

    Опишите действия с VCS при единоличной работе с хранилищем.

Ответ: при единоличной работе с хранилищем все изменения, созданные пользователем, не влияют на общий репозиторий.

    Опишите порядок работы с общим хранилищем VCS.

Ответ: из общего хранилища можно получать изменения проекта.

    Каковы основные задачи, решаемые инструментальным средством git?

Ответ: git позволяет несольким людям работать над одним проектом.

    Назовите и дайте краткую характеристику командам git.

Ответ: add - добавить файлы в коммит, push - отправить коммит на удалённый репозиторий; pull - импортировать проект с удалённого репозитория.

    Приведите примеры использования при работе с локальным и удалённым репозиториями.

Ответ:

    Что такое и зачем могут быть нужны ветви (branches)?

Ответ: создав новую ветвь, можно, не вредя проекту, работать над конкретной частью проекта.

    Как и зачем можно игнорировать некоторые файлы при commit?

Ответ: some files may well be user specific.


# Выводы

В результате выполнения лабораторной и самостоятельной работ были получены прикладные навыки работы с системой контроля версий git, а значит, цель работы была достигнута.

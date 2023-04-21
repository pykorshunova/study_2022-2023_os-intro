---
# Front matter
lang: ru-RU
title: "Индивидуальный проект"
subtitle: "Этап 5"
author: "Коршунова Полина"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавить к сайту остальные элементы: сделать запись персонального проекта, а также разместить два поста.

# Задание

Добавить к сайту все остальные элементы:

	Сделать записи для персональных проектов.

	Сделать пост по прошедшей неделе.

	Добавить пост на тему по выбору.

		Языки научного программирования.

# Выполнение лабораторной работы

Сначала я выполнила команду ~/bin/hugo server, чтобы получить ссылку на локальный сайт и просматривать там изменения. Затем я добавила свой проект и проверила его на локальном сайте.

![Добавление проекта и проект на локальном сайте.](image/1.png){ #fig:001 width=70% }

Далее я создала два поста с помощью команды ~/bin/hugo new post/название_поста. Мои посты были на тему прошлой недели и о языках научного программирования.

![Создание двух постов.](image/2.png){ #fig:002 width=70% }

Я заполнила пост о прошедшей неделе необходимой информацией, сохранила его и проверила на локальном сайте.

![Заполнение поста о прошлой неделе и пост на локальном сайте.](image/3.png){ #fig:003 width=70% }

Далее заполнила второй пост о науке и программировании, затем сохранила и проверила изменения на локальном сайте.

![Заполнение поста о науке и программировании и пост на локальном сайте. ](image/4.png){ #fig:004 width=70% }

Затем я выполнила исполняемый файл ~/bin/hugo в каталоге blog, и проверила изменения в public с помощью команды git status. 

После того, как я убедилась, что в public произошли необходимые изменения, я запушила(отправила) изменения на сервер.

Далее я также запушила(отправила) изменения в blog на сервер, предварительно выполнив команду git status для проверки изменений.

После того, как все изменения отправились на сервер, я открыла мой публичный сайт и проверила все изменения. Убедилась в корректности выполнения всех действий.

# Вовод

В ходе выполнения данного этапа я добавила к сайту остальные данные, разместила проект и создала два поста.



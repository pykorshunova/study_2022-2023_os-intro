---
## Front matter
title: "Индивидуальный проект"
subtitle: "Stage 2"
author: "Коршунова П. Ю."

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

Приобрести практические навыки работы с собственным сайтом


# Выполнение лабораторной работы

1. Размещаю фотографию владельца сайта (рис. @fig:001).

![Фото](image/1.png){#fig:001 width=90%}

2. Размещаю краткое описание владельца сайта, информацию об интересах, информацию об образовании (рис. @fig:002) (рис. @fig:003)

![инфа 1](image/2.png){#fig:002 width=90%}

![инфа 2](image/3.png){#fig:003 width=90%}

3. Делаю пост по прошедшей неделе (рис. @fig:004) (рис. @fig:005) (рис. @fig:006)

![пост 1](image/4.png){#fig:004 width=90%}

![пост2](image/5.png){#fig:005 width=90%}

![пост 3](image/6.png){#fig:006 width=90%}

4. Добавляю пост на тему по выбору (рис. @fig:007) (рис. @fig:008) (рис. @fig:009)

![пост 4](image/7.png){#fig:007 width=90%}

![пост 5](image/8.png){#fig:008 width=90%}

![пост 6](image/9.png){#fig:009 width=90%}
# Выводы

Я приобрела практические навыки создания сайта

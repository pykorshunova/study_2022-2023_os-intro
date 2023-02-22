---
## Front matter
title: "Отчет по выполнению индивидуального проекта"
subtitle: "Первый этап"
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

Получить практические навыки создания собственного сайта


# Выполнение лабораторной работы

1. Скачиваю файл hugo, распаковываю его, создаю папку bin, добавляю hugo туда (рис. @fig:001).

![Скачивание файл hugo](image/1.png){#fig:001 width=90%}

2. Создаю новый репозиторий blog (рис. @fig:002) 

![Создание нового репозитория blog](image/2.png){#fig:001 width=90%}

3. Клонирую созданный репозиторий (рис. @fig:003)

![Клонирование созданного репозитория](image/3.png){#fig:003 width=90%}

4. Перехожу в blog и скачиваю файлы hugo (рис. @fig:004)

![Перехожу в blog и скачиваю файлы hugo](image/4.png){#fig:004 width=90%}

5. Удаляю файл public и генерирую ссылку на сайт (рис. @fig:005)

![Удаляю файл public и генерирую ссылку на сайт](image/5.png){#fig:005 width=90%}

6. Перехожу по созданной ссылке (рис. @fig:006)

![Переход по созданной ссылке](image/6.png){#fig:006 width=90%}

7. Создаю новый репозиторий (рис. @fig:007)

![Создание нового репозитория](image/7.png){#fig:007 width=90%}

8. Переключаюсь на ветку main, создаю файл README.md, добавляю его на github, вывожу текущую рабочую директорию (рис. @fig:008)

![Создаю файл README.md](image/8.png){#fig:008 width=90%}

9. Добавляю # к public, чтобы было возможно копирование (рис. @fig:009)

![Исправляю ошибку](image/9.png){#fig:009 width=90%}

10. Добавляю сайт на github (рис. @fig:010) (рис. @fig:011)

![Добавляю сайт на github](image/10.png){#fig:010 width=90%}

![Добавляю сайт на github](image/11.png){#fig:011 width=90%}

# Выводы

В ходе данного этапа проекта я приобрела практические навыки создания сайта



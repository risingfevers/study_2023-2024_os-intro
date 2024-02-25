---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Предмет: Операционные системы"
author: "Иваненко Дмитрий Кириллович"

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

Научиться работе с pandoc, texlive. Научиться работать с markdown

# Задание

Создать отчет по лабораторной работе №2

# Выполнение лабораторной работы

1) переношу скрины в папку lab02/report/images:

![](image/q1.png){#fig:001 width=70%}

2) начинаю выполнять отчет в файле report.md:

![](image/q2.png){#fig:001 width=70%}

3) перехожу в директорию, где находиться report.md:

![](image/q3.png){#fig:001 width=70%}

4) конвертирую в pdf специальной командой:

![](image/q4.png){#fig:001 width=70%}

5) конвертирую в doxc специальной командой:

![](image/q5.png){#fig:001 width=70%}

6) финальный результат:

4) конвертирую в pdf специальной командой:

![](image/q6.png){#fig:001 width=70%}

# Выводы

Научились работе с markdown, научился оформлять отчеты.

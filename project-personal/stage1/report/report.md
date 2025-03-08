---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап"
author: "Хохлачёва Полина Дмитриевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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



# Выполнение лабораторной работы

распаковка пакета (рис. [-@fig:001]).

![распаковка пакета](image/1.jpg){#fig:001 width=70%}

задаём имя(рис. [-@fig:002]).

![имя](image/2.jpg){#fig:002 width=70%}

клонирование в blog(рис. [-@fig:003]).

![клонирование](image/3.jpg){#fig:003 width=70%}

загрузка go(рис. [-@fig:004]).

![загрузка](image/4.jpg){#fig:004 width=70%}

загрузка hugo server(рис. [-@fig:005]).

![загрузка](image/5.jpg){#fig:005 width=70%}

запуск сайта(рис. [-@fig:006]).

![запуск](image/6.jpg){#fig:006 width=70%}

удаление public(рис. [-@fig:007]).

![удаление](image/7.jpg){#fig:007 width=70%}

# Выводы

Проходя первый этап мы получили ньовые навыки



---
## Front matter
title: "Лабораторная работа № 4"
subtitle: "Продвинутое использование git."
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
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы
Получение навыков правильной работы с репозиториями git.

# Выполнение лабораторной работы

установка git(рис. [-@fig:001]).

![Установка](image/1.jpg){#fig:001 width=70%}

Установка Node.js(рис. [-@fig:002]).

![Установка](image/2.jpg){#fig:002 width=70%}

Общепринятые коммиты(рис. [-@fig:003]).

![коммиты](image/3.jpg){#fig:003 width=70%}

Создание репозитория git(рис. [-@fig:004]).

![коммиты](image/4.jpg){#fig:004 width=70%}

заполняем параметры пакета(рис. [-@fig:005]).

![коммиты](image/5.jpg){#fig:005 width=70%}

Конфигурация(рис. [-@fig:006]).

![Конфигурация](image/6.jpg){#fig:006 width=70%}

добавление в журнал(рис. [-@fig:007]).

![Добавление](image/7.jpg){#fig:007 width=70%}

работа с репозиторием(рис. [-@fig:008]).

![Репозиторий](image/8.jpg){#fig:008 width=70%}

отправляем данные(рис. [-@fig:009]).

![Отправка](image/9.jpg){#fig:009 width=70%}

создаём релиз(рис. [-@fig:010]).

![создание](image/10.jpg){#fig:010 width=70%}




# Выводы
Выполняя лабораторную работу мы получили навыки правильной работы с репозиториями git.


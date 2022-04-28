---
## Front matter
title: "1 этап индивидуального проекта"
subtitle: "Операционные системы"
author: "Балханова Алтана Юрьевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
pandoc_args: --top-level-division=chapter
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
biblio-style: "numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=numeric
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

Разместить на Github pages заготовку для персонального сайта.

# Задание

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.


# Выполнение работы
1. Установила hugo: (рис. [-@fig:001])

![установка hugo](image/Screenshot_01.png){ #fig:001 width=70% }

1. Скачала шаблон темы сайта и разместила его на github: (рис. [-@fig:002])

![шаблон сайта](image/Screenshot_2.png){ #fig:002 width=70% }

1. Создала сайт(рис. [-@fig:003] и прикрепила к github(рис. [-@fig:004]): 

![создание сайта](image/Screenshot_1.png){ #fig:3 width=70% }

![авторизация](image/Screenshot_02.png){ #fig:004 width=70% }

1. Установила URL сайта [https://aybalkhanova.netlify.app](https://aybalkhanova.netlify.app): (рис. [-@fig:005])

![URL сайта](image/Screenshot_3.png){ #fig:005 width=70% }

1. Так выглядит скачанный шаблон сайта: (рис. [-@fig:006], [-@fig:007])

![шаблон сайта](image/Screenshot_4.png){ #fig:006 width=70% }

![шаблон сайта](image/Screenshot_5.png){ #fig:007 width=70% }

1. Изменила имя и организацию: (рис. [-@fig:008]) 

![сайт](image/Screenshot_6.png){ #fig:008 width=70% }

# Выводы

- Я разместила на github шаблон сайта


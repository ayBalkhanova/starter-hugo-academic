---
## Front matter
title: "2 этап индивидуального проекта"
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

Добавить к сайту данные о себе, сделать первые посты.

# Задание

- Список добавляемых данных.
	- Разместить фотографию владельца сайта.
	- Разместить краткое описание владельца сайта (Biography).
	- Добавить информацию об интересах (Interests).
	- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:
	- Управление версиями. Git.
	- Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение работы
1. Добавила данные о себе: биографию, интересы, образование, фотографию:

	![Посты](image/Screenshot_7.png){ #fig:001 width=70% }

	![Данные о себе](image/Screenshot_4.png){ #fig:001 width=70% }
	
1. Сделала пост о выполнении индивидуального проекта на прошлой неделе:
	
	![Маркдаун](image/Screenshot_6.png){ #fig:001 width=70% }
		
	![пост о выполнении индивидуального проекта](image/Screenshot_2.png){ #fig:001 width=70% }
		
1. Сделала пост об управлении версиями. Git.
	
	![Маркдаун](image/Screenshot_5.png){ #fig:001 width=70% }
		
	![пост об управлении версиями](image/Screenshot_1.png){ #fig:001 width=70% }
		
1. Посты:
	
	![Посты](image/Screenshot_3.png){ #fig:001 width=70% }
	
# Выводы

- Я написала свою биографию и первые посты.


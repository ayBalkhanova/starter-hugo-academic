---
## Front matter
title: "4 этап индивидуального проекта"
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

Добавить к сайту ссылка на научаные и библиометрические ресурсы, написать посты.

# Задание

- Добавить к сайту ссылки на научные и библиометрические ресурсы.
	- Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
		- eLibrary : https://elibrary.ru/;
		- Google Scholar : https://scholar.google.com/;
		- ORCID : https://orcid.org/;
		- Mendeley : https://www.mendeley.com/;
		- ResearchGate : https://www.researchgate.net/;
		- Academia.edu : https://www.academia.edu/;
		- arXiv : https://arxiv.org/;
		- github : https://github.com/.
	- Сделать пост по прошедшей неделе.
	- Добавить пост на тему по выбору:
		- Оформление отчёта.
		- Создание презентаций.
		- Работа с библиографией.

# Выполнение работы
1. Зарегистрировалась на соответствующих ресурсах и разместила на них ссылка на сайте:

	![Ссылка](image/Screenshot_1.png){ #fig:001 width=70% }

	![Маркдаун](image/Screenshot_2.png){ #fig:001 width=70% }
	
1. Сделала пост о выполнении индивидуального проекта на прошлой неделе:
		
	![Пост о выполнении индивидуального проекта](image/Screenshot_4.png){ #fig:001 width=70% }
		
1. Сделала пост об оформлении отчёта.
		
	![Пост об оформлении отчёта](image/Screenshot_3.png){ #fig:001 width=70% }
		
1. Посты:
	
	![Посты](image/Screenshot_5.png){ #fig:001 width=70% }
	
# Выводы

- Я добавила к сайту cсылка на научные и библиметрические ресурсы, сделала пост по выполнению индивидуального проекта на прошедшей неделе и сделала пост об оформлении отчёта.


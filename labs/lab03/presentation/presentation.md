---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "По теме: Язык разметки Markdown"
author: "Выполнил: Чубаев Кирилл Евгеньевич, НММбд-01-24"

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
biblatex: false
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

Целью данной работы является научиться оформлять отчёты с помощью легковесного языка разметки Markdown.


# Ход выполнения лабораторной работы

1. Я открыл терминал и перешел в каталог курса, сформированный при выполнении лабораторной работы №2, и обновил локальный репозиторий:

![](image/1.png)

2. Далее провёл компиляцию шаблона с использованием Makefile. Для этого ввёл команду make для проверки работоспособности команды. Далее с помощю команды make clean удалил файлы.

![](image/2.png)
![](image/3.png)

3. Я открыл файл report.md и начал выполнять задание данной лабораторной работы, а именно: полный отчёт лабораторной работы №2. В свой отчёт я добавил: введение, основную часть, заключение и список литературы:

![](image/4.png)

4. Для корректного изображения скриншотов я разместил их в каталоге image:

![](image/5.png)
![](image/6.png)
![](image/7.png)

5. Далее с помощью команды make я скомпилировал файлы report.docx и report.pdf

6. Выполненный отчёт с использованием Markdown я загрузил на GitHub:

# Вывод

В ходе выполнения данной лабораторной работы я научился оформлять отчёты с помощью легковесного языка разметки Markdown. 
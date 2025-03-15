---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "По теме: Настройка рабочей среды"
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

Цель данной работы - настроить рабочую среду, научиться пользоваться менеджером паролей pass и командой chezmoi.


# Выполнение лабораторной работы

1. Я установил команду pass и просмотрел список ключей:

![](image/1.png)

2. Далее инициализировал хранилище:

![](image/2.png)

3. Затем создал структуру с git:

![](image/3.png)

4. Потом задал адрес репозитория на хостинге и выполнил команды git pull и git push для синхронизации:

![](image/4.png)

5. Далее я установил плагин browserpass для Firefox:

![](image/5.png)

6. Потом установил дополнительное программное обеспечение и дополнительные шрифты:

![](image/6.png)
![](image/7.png)

7. Затем я начал создавать собственный репозиторий с помощью утилит:

![](image/8.png)

8. Инициализировал chezmoi с моим репозиторием dotfiles:

![](image/9.png)

9. Потом установил свои dotfiles на новый компьютер с помощью одной команды:

![](image/10.png)

10. Далее я поставил настройку чтобы изменения фиксировались и отправлялись автоматически в репозиторий:

![](image/11.png)

# Выводы

В ходе данной лабораторной работы я настроил свою рабочую среду и научился пользоваться менеджером паролей pass и командной chezmoi.

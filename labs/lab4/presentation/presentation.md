---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе 4
subtitle: Дискреционное разграничение прав в Linux. Расширенные атрибуты
author:
  - Саттарова В.В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 30 сентября 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Саттарова Вита Викторовна
  * студент НФИбд-02-20, 1032201655
  * Российский университет дружбы народов

:::
::::::::::::::

# Вводная часть

## Актуальность и прагматика

- Практические навыки работы в консоли с расширенными атрибутами файлов помогут при выполнении дальнейших работ и научат настраивать особый доступ пользователям к файлам
- Дискреционное разграничения доступа в современных системах помогает обеспечить безопасность системы при работе большого числа пользоваетлей

## Цели 

- Закрепить практические навыки работы в консоли с расширенными атрибутами файлов.
- Закрепить теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

## Задачи

- Вспомнить теоретические основы атрибутов файлов и директорий в ОС Linux.
- Выполнить все пункты, указанные в методических рекомендациях к лабораторной работе.
- Исследовать возможность выполнения действий при расширенном атрибуте -a.
- Исследовать возможность выполнения действий при расширенном атрибуте -i.
- Написать отчёт, проанализировав результаты, полученные в ходе выполнения лабораторной работы.

## Исследование выполнения различных действий без расширенных атрибутов
![Выполнение действий отсутствии расширенных атрибутов](./image/10.jpg)

## Исследование выполнения различных действий с расширенным атрибутом
![Выполнение действий с расширенным атрибутом -i](./image/11.jpg)

# Результаты

- Вспомнены теоретические основы атрибутов файлов и директорий в ОС Linux.
- Был проведён анализ, за что отвечают разные расширенные атрибуты доступа и как они влияют на возможность выполнения действий пользователем.  
- Написан отчёт к лабораторной работе.
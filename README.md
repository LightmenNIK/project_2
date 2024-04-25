# Анализ вакансий из HeadHanter

## Общее описание проекта

Проект по анализу вакансий с сайта для поиска работы [HeadHanter](https://hh.ru/) в рамках курса "Профессия Data Science" от [SkillFactory](https://skillfactory.ru/).

Работа производится с данными представляющими из себя несколько связанных между собой таблиц. Доступ к ним осуществляется посредством [SQL-запросов](https://blog.skillfactory.ru/glossary/sql/) с помощью библиотеки [psycopg2](https://wiki.postgresql.org/wiki/Using_psycopg2_with_PostgreSQL)
![Схематическое изображение таблиц.](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@SQL_pj2_2_1.png)

**Проект включает в себя четыре основных этапа:**

* Предварительный анализ данных

* Детальный анализ вакансий

* Анализ работодателей 

* Предметный анализ

**Целью проекта** является анализ данных, отработка навыков написания SQL-запросов

## Использованные инструменты и библиотеки

Проект выполнен в формате .ipynb c использованием языка програмирования python (3.11.4). Основыне этапы проекта представлены в виде выполнения заданий в отдельных ячейках. По каждому этапу представлен краткий вывод. Общий вывод с визуализацией данных представлен в конце работы.

В работе использованы следующие библиотеки:
---

* pandas (2.1.4)

* plotly.express (5.18.0)

* psycopg2 (2.9.9)
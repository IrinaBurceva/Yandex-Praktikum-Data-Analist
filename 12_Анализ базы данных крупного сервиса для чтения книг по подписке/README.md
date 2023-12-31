# Анализ базы данных крупного сервиса для чтения книг по подписке

## Задача проекта:

Проанализировать базу данных крупного сервиса для чтения книг по подписке и выполнить задания с помощью SQL-запросов из Python.

## Описание проекта:

1) Посчитайть, сколько книг вышло после 1 января 2000 года;

2) Для каждой книги посчитать количество обзоров и среднюю оценку;

3) Определить издательство, которое выпустило наибольшее число книг толще 50 страниц — исключить из анализа брошюры;

4) Определить автора с самой высокой средней оценкой книг — учитывать только книги с 50 и более оценками;

5) Посчитать среднее количество обзоров от пользователей, которые поставили больше 48 оценок.

## Выводы по проекту:

На основании выполненных исследований получили следующие выводы по базе данных:

821 книга вышла после 1 января 2000 года.

Книги, которые имеют самое большое количество обзоров - "Twilight", "Water for Elephants", "The Glass Castle", "Harry Potter and the Prisoner of Azkaban", "The Curious Incident of the Dog in the Night-Time ". Каждая из них получила среднюю оценку пользователей: 4.

Издательство, которое выпустило наибольшее число книг больше 50 страниц - Penguin Books. Количество таких выпущенных книг у издательства - 42 шт.

Автор с самой высокой средней оценкой книг среди книг с 50 и более оценками - J.K. Rowling/Mary GrandPré. Средний рейтинг его книг - 4.29.

Среднее количество обзоров от пользователей, которые поставили более 48 оценок, - 24.0.

## Навыки и инструменты:

Python, Pandas, SQLAlchemy, PostgreSQL

## Статус проекта:

Завершен


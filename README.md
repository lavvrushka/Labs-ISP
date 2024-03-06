# Лабораторная работа №1: Создание калькулятора с использованием .NET MAUI и XAML

## Цель работы
Целью данной лабораторной работы является знакомство с фреймворком .NET MAUI и основами языка разметки XAML.

## Задача работы
Основной задачей работы является создание простого приложения калькулятора с помощью .NET MAUI. Дополнительно требуется реализовать функцию вычисления остатка от деления (mod).

## Важно
Это лишь простой пример приложения калькулятора для демонстрации возможностей .NET MAUI и XAML. Вы можете дополнить его или изменить по своему усмотрению.

# Лабораторная работа №2: Управление UI из вторичного потока

## Цель работы
Целью данной лабораторной работы является углубленное знакомство с фреймворком .NET MAUI и основами языка разметки XAML.

## Задача работы
Основной задачей работы является научиться управлять интерфейсом приложений из вторичного потока.

### Условие
По клику на кнопку Start асинхронно (await, async Task) запускается вычисление интеграла функции y=sin(x) на участке от 0 до 1 (использовать метод прямоугольников). Для итерации использовать шаг 0,00000001. Для увеличения времени выполнения вычисления на каждой итерации можно ввести задержку в виде цикла из 100000 формальных вычислений (например, умножения двух чисел). Подобрать значения так, чтобы вычисление занимало около секунд.

ProgressBar должен отображать прогресс вычисления. Также прогресс должен выводиться в процентном отношении. Кнопка Cancel предназначена для отмены вычисления (использовать CancellationToken).

Надпись в верхней части экрана должна меняться на следующие сообщения:
- "Вычисление", когда идет вычисление интеграла (по клику кнопки Start);
- результат вычисления интеграла по завершении вычисления;
- "Задание отменено", если была нажата кнопка Cancel во время вычисления.

# Лабораторная работа №3: Работа с базой данных

## Цель работы
Целью данной лабораторной работы является знакомство с ORM SQLite.Net.

## Задача работы
Основной задачей работы является научиться сохранять данные в локальной базе данных и выводить списки данных на экран.

### Условие
Тема работы: Коктейли – ингредиенты.

# Лабораторная работа №4: Работа с REST API сервисом

## Цель работы
Цель работы: Изучение возможности использования интернет-соединения в мобильных приложениях.

## Задача работы
Основной задачей работы является научиться получать, обрабатывать и отображать данные с веб-сервисов.

### Условие
Добавить в проект страницу – «Конвертер валют».

Конвертер должен:
1. Показывать официальный курс белорусского рубля, установленный Национальным банком Республики Беларусь на выбранную дату для следующих валют:
   - Российский рубль
   - Евро
   - Доллар США
   - Швейцарский франк
   - Китайский юань
   - Фунт стерлингов
2. Выбирать валюту для конвертации
3. Позволять выполнять пересчет суммы в белорусских рублях в выбранную иностранную валюту (см. п. 2.) и обратно

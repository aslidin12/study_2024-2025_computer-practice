---
# Front matter
# Front matter
lang: ru-RU
title: "Компьютерный практикум по статистическому анализу данных"
subtitle: "Отчёт по лабораторной работе №4: Линейная алгебра"
author: "Ахлиддинзода Аслиддин"
institute:
  - Российский университет дружбы народов, Москва, Россия

# i18n babel
babel-lang: russian
babel-otherlangs: english

# Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---


# Цель лабораторной работы

Основной целью работы является изучение возможностей специализированных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной алгебры.

# Выполнение лабораторной работы: Поэлементные операции над многомерными массивами

![Поэлементные операции сложения и произведения элементов матрицы](image/1.PNG){ #fig:001 width=80% height=75% }

#  1. Поэлементные операции над многомерными массивами

![Использование возможностей пакета Statistics для работы со средними значениями](image/2.PNG){ #fig:002 width=80% height=75% }

#  2. Tранспонирование, след, ранг, определитель и инверсия матрицы

![Использование библиотеки LinearAlgebra для выполнения определённых операций](image/3.PNG){ #fig:003 width=80% height=75% }

# 2. Tранспонирование, след, ранг, определитель и инверсия матрицы

![Использование библиотеки LinearAlgebra для выполнения определённых операций](image/4.PNG){ #fig:004 width=80% height=75% }


# 3. Вычисление нормы векторов и матриц, повороты, вращения

![Использование LinearAlgebra.norm(x)](image/5.PNG){ #fig:005 width=80% height=75% }

# 3. Вычисление нормы векторов и матриц, повороты, вращения

![Вычисление нормы для двумерной матрицы](image/6.PNG){ #fig:006 width=80% height=75% }

# 4. Матричное умножение, единичная матрица, скалярное произведение

![Примеры матричного умножения, единичной матрицы и скалярного произведения](image/7.PNG){ #fig:007 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Решение систем линейный алгебраических уравнений Ax = b](image/8.PNG){ #fig:008 width=80% height=75% }

# 5. Факторизация. Специальные матричные структуры

![Пример вычисления LU-факторизации и определение составного типа факторизации для его хранения](image/9.PNG){ #fig:009 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Пример решения с использованием исходной матрицы и с использованием объекта факторизации](image/10.PNG){ #fig:010 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Пример вычисления QR-факторизации и определение составного типа факторизации для его хранения](image/11.PNG){ #fig:011 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Примеры собственной декомпозиции матрицы A](image/12.PNG){ #fig:012 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Примеры работы с матрицами большой размерности и специальной структуры](image/13.PNG){ #fig:013 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Пример добавления шума в симметричную матрицу](image/14.PNG){ #fig:014 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Пример явного объявления структуры матрицы](image/15.PNG){ #fig:015 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Использование пакета BenchmarkTools](image/16.PNG){ #fig:016 width=80% height=75% }


# 5. Факторизация. Специальные матричные структуры

![Примеры работы с разряженными матрицами большой размерности](image/17.PNG){ #fig:017 width=80% height=75% }


# 6. Общая линейная алгебра

![Решение системы линейных уравнений с рациональными элементами без преобразования в типы элементов с плавающей запятой](image/18.PNG){ #fig:018 width=80% height=75% }


# 7. Самостоятельная работа

![Выполнение задания "Произведение векторов"](image/19.PNG){ #fig:019 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Система линеный уравнений". Пункт 1](image/20.PNG){ #fig:020 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Система линеный уравнений". Пункт 2](image/21.PNG){ #fig:021 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Операции с матрицами". Пункт 1](image/22.PNG){ #fig:022 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Операции с матрицами". Пункт 2](image/23.PNG){ #fig:023 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Операции с матрицами". Пункт 2](image/24.PNG){ #fig:024 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Операции с матрицами". Пункт 2](image/25.PNG){ #fig:025 width=80% height=75% }


# 5. Самостоятельная работа

![Выполнение задания "Операции с матрицами". Пункт 3](image/26.PNG){ #fig:026 width=80% height=75% }

# 5. Самостоятельная работа

![Выполнение задания "Линейные модели экономики"](image/27.PNG){ #fig:027 width=80% height=75% }


# Вывод

В ходе выполнения лабораторной работы были изучены возможности специализированных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной алгебры.


# Список литературы. Библиография

[1] Julia Documentation: https://docs.julialang.org/en/v1/

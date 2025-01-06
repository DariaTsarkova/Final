## Задание
Есть мнение: раньше снимали настоящее кино, не то что сейчас. Ваша задача — проверить это утверждение, используя файлы с рейтингами фильмов movies_stats.csv. То есть проверить, верно ли, что с ростом года выпуска фильма средний рейтинг становится ниже.

При этом мы не будем затрагивать субъективные факторы этих рейтингов, а пройдёмся по следующему алгоритму:

В переменную years запишите список из всех годов с 1950-го по 2010-й.

Напишите функцию production_year, которая каждой строке из названия фильма выставляет год выпуска (год выпуска берём из столбца title). Не все названия фильмов содержат год выпуска в одинаковом формате, поэтому используйте следующий алгоритм:

для каждой строки пройдите по всем годам списка years;
если номер года присутствует в названии фильма, то функция возвращает этот год как год выпуска;
если ни один из номеров года списка years не встретился в названии фильма, то возвращается 1900 год.
Запишите год выпуска фильма по алгоритму пункта 2 в новый столбец ‘year’.

Посчитайте средний рейтинг всех фильмов для каждого значения столбца ‘year’ и отсортируйте результат по убыванию рейтинга.
# Описания проекта - Музыка больших городов
## Данные
В наличии были следующие данные о прослушиваниях треков в сервисе Яндекс.Музыка:

Название трека
Исполнитель
Жанр
Город
День прослушивания
Время прослушивания
## Задача
Провести сравнение музыкальных предпочтений у пользователей Яндекс.Музыки, проживающих в Москве и Санкт-Петербурге. Сравнить прослушивания в понедельник, среду и пятницу по городам, а также сравнить жанры, которые слушают пользователи утром в понедельник и вечером в пятницу в Москве и Санкт-Петербурге.

Навыки и инструменты
Предобработка данных, pandas

## Итоги исследования
При проверке гипотез было установлено:

День недели по-разному влияет на активность пользователей в Москве и Петербурге. Первая гипотеза полностью подтвердилась.

Музыкальные предпочтения не сильно меняются в течение недели как для Москвы, так и для Петербурга. Небольшие различия заметны в начале недели, по понедельникам:

в Москве слушают музыку жанра “world”,
в Петербурге — джаз и классику.
Таким образом, вторая гипотеза подтвердилась лишь отчасти. Этот результат мог оказаться иным, если бы не пропуски в данных.

Во вкусах пользователей Москвы и Петербурга больше общего чем различий. Предпочтения жанров в Петербурге напоминают московские. Третья гипотеза не подтвердилась. Если различия в предпочтениях и существуют, на основной массе пользователей они незаметны.
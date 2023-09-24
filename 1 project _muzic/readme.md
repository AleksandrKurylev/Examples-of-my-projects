<h1 align="center"> Исследование данных сервиса “Яндекс.Музыка” </h1>

<h3>Описание проекта:</h3> 
На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.
<br><br>

Цель исследования — проверка трёх гипотез:

- Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному.
- В понедельник утром в Москве преобладают одни жанры, а в Петербурге — другие. Так же и вечером пятницы преобладают разные жанры — в зависимости от города.
- Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.
***
### Ход исследования

Данные о поведении пользователей получаем из файла yandex_music_project.csv. О качестве данных ничего не известно.
Поэтому перед проверкой гипотез понадобится обзор данных.
Проверим данные на ошибки и оценим их влияние на исследование. Затем, на этапе предобработки найдем возможность 
исправить самые критичные ошибки данных.

**Таким образом, исследование пройдёт в три этапа:**
1. Обзор данных.
2. Предобработка данных.
3. Проверка гипотез.
***
### Результаты проекта
Мы проверили три гипотезы и установили:

1. День недели по-разному влияет на активность пользователей в Москве и Петербурге. 

Первая гипотеза полностью подтвердилась.

2. Музыкальные предпочтения не сильно меняются в течение недели — будь то Москва или Петербург. Небольшие различия заметны в начале недели, по понедельникам:
* в Москве слушают музыку жанра “world”,
* в Петербурге — джаз и классику.

Таким образом, вторая гипотеза подтвердилась лишь отчасти. Этот результат мог оказаться иным, если бы не пропуски в данных.

3. Во вкусах пользователей Москвы и Петербурга больше общего чем различий. Вопреки ожиданиям, предпочтения жанров в Петербурге напоминают московские.

Третья гипотеза не подтвердилась. Если различия в предпочтениях и существуют, на основной массе пользователей они незаметны.
***
<h3>Стек проекта:</h3>

Среда разработки - `Jupyter Notebook`; <br>
Язык программирования - `Python`; <br>
Библиотеки - `Pandas`. <br>
<br>


# Выявление закономерностей определяющих успешность игры

**Описание проекта**  
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. В распоряжении данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. 

**Задание**  
Провести исследовательский анализ данных и ответить на вопросы:
- Сколько игр выпускалось в разные годы? 
- Важны ли данные за все периоды?
- Как менялись продажи по платформам? 
- Выбрать платформы с наибольшими суммарными продажами и построить распределение по годам. 
- За какой характерный срок появляются новые и исчезают старые платформы?
- Определить актуальный период в результате исследования предыдущих вопросов. Основной фактор — эти данные помогут построить прогноз на 2017 год.
- Какие платформы лидируют по продажам, растут или падают? Выберать несколько потенциально прибыльных платформ.
- Как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Построить диаграмму рассеяния и посчитайте корреляцию между отзывами и продажами. Соотнести полученные результаты с продажами игр на других платформах.
- Изучить общее распределение игр по жанрам. Какие жанры самые прибыльные? Выделяются ли жанры с высокими и низкими продажами?
- Составить портрет пользователя каждого региона. Определить для пользователя каждого региона (NA, EU, JP):
    * Самые популярные платформы (топ-5);
    * Самые популярные жанры (топ-5); 
    * Влияет ли рейтинг ESRB на продажи в отдельном регионе?
- Проверить гипотезы:
    * Средние пользовательские рейтинги платформ Xbox One и PC одинаковые; 
    * Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.

**Описание данных**
* `Name` — название игры
* `Platform` — платформа
* `Year_of_Release` — год выпуска
* `Genre` — жанр игры
* `NA_sales` — продажи в Северной Америке (миллионы проданных копий)
* `EU_sales` — продажи в Европе (миллионы проданных копий)
* `JP_sales` — продажи в Японии (миллионы проданных копий)
* `Other_sales` — продажи в других странах (миллионы проданных копий)
* `Critic_Score` — оценка критиков (максимум 100)
* `User_Score` — оценка пользователей (максимум 10)
* `Rating` — рейтинг от организации ESRB (англ. Entertainment Software Rating Board).

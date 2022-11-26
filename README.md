# Репозиторий проектов и тестовых заданий.
Представленные проекты и тестовые задания были выполнены в ходе обучения в Яндекс.Практикуме по профессии "Аналитик данных".

П.П. | Название проекта | Тема | Описание |	Используемые библиотеки
--- | --- | --- | --- | ---
01| Исследование данных сервиса “Яндекс.Музыка”. |Базовый Python| Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница). |	pandas
02| Исследование надёжности заёмщиков — анализ банковских данных. | Предобработка данных | На основе данных кредитного отдела банка проведено исследование влияние разных факторов на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные. | pandas, pymystem3
03| Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости. | Исследовательский анализ данных | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.| pandas, matplotlib, seaborn, geopy 
04|
05|
06|
07|
08|
09| Анализ убытков приложения ProcrastinatePRO+.| Анализ бизнес-показателей | Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate и т.д. | pandas, matplotlib, seaborn, numpy, datetime
10| Исследование базы данных сервиса Stackoverflow. | SQL | В этом исследовании работа идёт с базой данных StackOverflow. Были исследованы предоставленные данные, сформироны требуемые выгрузки данных с помощью SQL, посчитаны различные продуктовые метрики. | pandas, matplotlib, seaborn, sqlalchemy
11|Определение выгодного тарифа для телеком компании. | Статистический анализ данных | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов в зависимости от тарифов и региона. Сделаны и выводы и даны рекомендации. | pandas, matplotlib, seaborn, datetime, scipy.stats
12| Проверка гипотез по увеличению выручки в интернет-магазине и оценка результатов A/B теста | Принятие решений в бизнесе | Проведена приоритизация гипотез по фреймворкам ICE и RICE и анализ результатов A/B-теста. Построены графики кумулятивной выручки, среднего чека, конверсии по группам и посчитана статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании было принято решение о нецелесообразности дальнейшего проведения теста.
13| Прогнозирование вероятности оттока клиентов.|Основы машинного обучения | На основе данных о посетителях сети фитнес-центров спрогнозировать вероятность оттока для каждого клиента в следующем месяце, сформировать с помощью кластеризации портреты пользователей. | pandas, matplotlib, seaborn, sklearn, scipy
14|
15|
16| Тестовое задание eLama | Тестовое задание |Используя лог.файлы ответить на вопросы: 1. Между какими событиями наибольший шаг; 2. Интервал времени до наступления какого события показывает наибольший разброс; 3. Какая задача прогнозирования выполняется дольше всего; 4. Какое количество задач прогнозирования может выполняться одновременно; 5. Перечислить forecastMarker которые не завершились успешно.|pandas, matplotlib, seaborn, numpy, datetime, io, requests

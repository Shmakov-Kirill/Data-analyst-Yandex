# Яндекс практикум - Аналитик данных

| Номер проекта| Название проекта | Описание проекта | Инструменты |
| ----------- | ----------- | ----------- | ----------- |
| 1 | [Исследование надежности заемщиков](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%B7%D0%B0%D0%B5%D0%BC%D1%89%D0%B8%D0%BA%D0%BE%D0%B2/da_project_1.ipynb) | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Выявил, что семейное положение, количество детей, уровень дохода и цель кредита влияют на своевременность выплат. Разработал портреты "идеального" и "рискового" клиентов и дал рекомендации по улучшению сбора данных. | Библиотека pandas |
| 2 | [Исследование объявлений о продаже квартир](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B5%20%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80/da_practicum_project_2.ipynb) | В нашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Провел анализ архивных данных о продаже квартир в Санкт-Петербурге и пригородах, выявив ключевые факторы, влияющие на цену недвижимости. Определил, что наибольшее влияние оказывают общая площадь, жилая площадь и площадь кухни, а количество комнат и этаж имеют меньший эффект. Провел коррекционный анализ, обработал пропуски и аномалии в данных, а также изучил динамику цен в зависимости от расстояния до центра города.  | pandas, matplotlib.pyplot, numpy  | 
| 3 | [Статистический анализ данных](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/da_practicum_project_3.ipynb) | Анализ популярного сервиса аренды самокатов GoFast. Мне передали данные о некоторых пользователях из нескольких городов, а также об их поездках. Провел комплексный анализ данных сервиса аренды самокатов GoFast. Осуществил визуализацию и описание демографических характеристик пользователей и параметров их поездок, выявив ключевые различия между пользователями с подпиской и без неё. На основе объединенных данных разработал метрики помесячной выручки, расстояний и времени поездок. Проверил статистические гипотезы о влиянии подписок на длительность и расстояние поездок. Разработал рекомендации для улучшения сервиса, включая маркетинговые стратегии и оптимизацию инфраструктуры| pandas, matplotlib.pyplot, numpy, scipy, stats, binom, math |
| 4 | [Сборный проект 1. Анализ закономерностей успешности компьютерных игр](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B7%D0%B0%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B9%20%D1%83%D1%81%D0%BF%D0%B5%D1%88%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D1%85%20%D0%B8%D0%B3%D1%80/da_practicum_project_4.ipynb) | Я работаю в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нам нужно выявить определяющие успешность игры закономерности. Провел анализ данных о видеоиграх с 1980 по 2016 год, выявив тенденции в выпуске игр, изменениях продаж по платформам и жанрам, а также влиянии отзывов на продажи. Обработал пропуски и привел данные к корректному виду для анализа. Оценил популярность платформ и жанров в разных регионах, выявил предпочтения игроков в Северной Америке, Европе и Японии. Проверил гипотезы о различиях в пользовательских рейтингах платформ и жанров. Результаты помогли лучше понять динамику игрового рынка и региональные особенности потребления. | pandas, numpy, matplotlib.pyplot, seaborn, scipy, stats |
| 5 | [Анализ бизнес-показателей приложения Procrastinate Pro+](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81-%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9/da_practicum_project_6.ipynb) | Несмотря на огромные вложения в рекламу развлекательного приложения Procrastinate Pro+, последние несколько месяцев компания терпит убытки. Задача — разобраться в причинах и помочь компании выйти в плюс. Провел анализ данных о визитах, заказах и расходах на рекламу, выявив ключевые факторы, влияющие на окупаемость рекламных кампаний. Определил, что пользователи Mac и iPhone, а также привлеченные через каналы TipTop, FaceBoom и LambdaMediaAds, не окупаются. Выявил рост стоимости привлечения пользователей и снижение конверсии с середины мая. Рекомендовал пересмотреть расходы на неэффективные каналы, улучшить удержание пользователей и оптимизировать рекламные кампании для повышения окупаемости. Особое внимание предложил уделить пользователям PC, которые показывают лучшую окупаемость. | pandas, numpy, datetime, timedelta, pyplot|
| 6 | [Приоритизация гипотез и A/B-тестирование для увеличения выручки в интернет-магазине](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%9F%D1%80%D0%B8%D0%BE%D1%80%D0%B8%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B3%D0%B8%D0%BF%D0%BE%D1%82%D0%B5%D0%B7/da_practicum_project_8.ipynb) | Я являюсь аналитиком крупного интернет-магазина. Вместе с отделом маркетинга был подготовлен список гипотез для увеличения выручки.В ходе данного проекта будут выполнены следующие задачи: анализ предоставленных данных, приоритизация гипотез, анализ A/B-теста. Провел анализ исходных данных и оценил эффективность гипотез с использованием фреймворков ICE и RICE. Провел анализ A/B теста, выявив статистически значимое увеличение среднего количества заказов на пользователя в группе B. Рекомендовал завершить тест и зафиксировать победу группы B. | pandas, matplotlib.pyplot, datetime, numpy, scipy |
| 7 | [Сборный проект 2. Анализ поведения пользователей мобильного приложения](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/da_practicum_project_9.ipynb) | Я работаю в стартапе, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи мобильного приложения. В ходе проекта будет исследовано следующее:1) Воронка продаж. Узнаем, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? На каких именно? 2) Результаты A/A/B-эксперимента. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. В результате анализа выяснил, что большинство пользователей покидают приложение на этапе перехода от главного экрана к экрану с предложениями. A/A/B тестирование изменений шрифта не выявило значимых различий в поведении пользователей. Рекомендовал провести дополнительные UX-исследования. | pandas, matplotlib.pyplot, numpy, seaborn, datetime, math, scipy, warnings, plotly.graph_objs |
| 8 | [Анализ рынка заведений общественного питания Москвы](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%80%D1%8B%D0%BD%D0%BA%D0%B0%20%D0%B7%D0%B0%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%D0%B1%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D1%8B/da_practicum_project_10.ipynb) | Проект направлен на анализ рынка общественного питания в Москве, чтобы помочь инвесторам из фонда "Shut Up and Take My Money" определить наиболее перспективный формат и расположение будущего заведения. В рамках исследования будет проведен глубокий анализ существующих кафе, ресторанов, баров, пиццерий и других типов заведений по различным критериям, включая распределение по районам, сетевость, популярность брендов, а также специализация на кофейнях, поскольку заказчики заинтересованы в открытии аналогичного "Central Perk" заведения из сериала "Друзья". В ходе анализа данных заведений Москвы были выявлены ключевые тенденции, полезные для открытия нового кафе. Наибольшее количество заведений приходится на кафе, а наименьшее — на булочные. Центральный административный округ лидирует по числу заведений и круглосуточных кафе. Средний чек в ЦАО и Западном округе достигает 1 000 рублей, а чашка капучино стоит около 184-189 рублей. Перспективные районы для открытия — Центральный округ (премиум сегмент) и Юго-Восточный (доступные цены). Выбор уникального формата и круглосуточного режима работы может стать конкурентным преимуществом.  | pandas, matplotlib.pyplot, numpy, seaborn, plotly, json, folium |
| 9 | [История TED-конференций](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/da_practicum_project_11.ipynb) | TED (от англ. technology, education, design — «технологии, образование, дизайн») — некоммерческий фонд, который проводит популярные конференции. На них выступают специалисты из разных областей и читают лекции на актуальные социальные, культурные и научные темы. В этом проекте я исследовал историю TED-конференций с помощью Tableau. В ходе работы я выяснил, что чаще всего выступления проходили в США, Канаде и Великобритании. Самые популярные темы выступлений - это глобальные проблемы, технологии и общественные проблемы. Чаще всего на автора приходится одно выступление. Сами авторы в основном из сферы журналистики, живописи и литературы. | Tableau |
| 10 | [Выпускной проект. Анализ оттока клиентов](https://github.com/Shmakov-Kirill/Data-analyst-Yandex/blob/main/da_practicum_project_12.ipynb) | Данный проект направлен на анализ клиентской базы регионального банка с целью выделения сегментов клиентов, которые склонны к уходу. Задача маркетингового отдела — проводить персонализированные действия для предотвращения оттока клиентов. Проект включает исследовательский анализ данных, формулировку и проверку гипотез, а также предоставление рекомендаций для маркетинга по мероприятиям, которые помогут удержать клиентов.  В рамках работы был проведен исследовательский анализ данных, проверены статистические гипотезы, выделены 4 ключевых сегмента клиентов, склонных к уходу и предложены рекомендации маркетинговому отделу для минимизации ухода клиентов. | pandas, matplotlib, seaborn, plotly, scipy.stats, numpy, proportions_ztest

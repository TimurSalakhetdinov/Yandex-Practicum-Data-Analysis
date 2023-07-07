# Yandex-Practicum
Данный репозиторий содержит проекты, которые я выполнил во время обучения на курсе Data Analytics в Yandex Practicum.

**Список проектов:**

[**5. Анализ развлекательного приложения Procrastinate Pro+**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-Data-Analysis/tree/main/Project%2001)

Задача: Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Наша задача — разобраться в причинах и помочь компании выйти в плюс.

Описание работы: Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным.

Навыки: Matplotlib, Pandas, Python, Seaborn, когортный анализ, продуктовые метрики, юнит-экономика

[**6. Анализ A/B-теста крупного интернет магазина**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-Data-Analysis/tree/main/Project%2002)

Задача: Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами. 

Описание работы: Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.

Навыки: A/B-тестирование, Matplotlib, Pandas, Python, SciPy, проверка статистических гипотез

[**7. Анализ результатов А/А/В эксперимента внедрения нового шрифта в мобильном приложении**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-Data-Analysis/tree/main/Project%2002)

Задача: На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования. 

Описание работы: В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.

Навыки: A/B-тестирование, Matplotlib, Pandas, Plotly, Python, Seaborn, визуализация данных, проверка статистических гипотез, продуктовые метрики, событийная аналитика

[**8. Рынок заведений общественного питания Москвы**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-Data-Analysis/tree/main/Project%2004)

Задача: Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов. 

Описание работы: Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в
котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена
презентация для инвесторов с рекомендациями. В построении графиков я использовали
библиотеки seaborn и plotly. 

Навыки: Python, Pandas, Seaborn, Plotly, визуализация данных

[**9. Рынок заведений общественного питания Москвы**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-Data-Analysis/tree/main/Project%2004)

Задача: Необходимо автоматизировать процесс получения информации для менеджеров анализа контента, предоставляя ответы на следующие вопросы:
* Сколько взаимодействий пользователей с карточками происходит в системе с разбивкойпо темам карточек?* Как много карточек генерируют источники с разными темами?* Как соотносятся темы карточек и темы источников? 

Описание работы: Работу над этим проектом я провел на удаленной машине в сервисе Yandex.Cloud. Мной был установлен PostgreSQL, развернута база данных. Затем я написал скрипт пайплайна, который позволил собирать данные за определенный временной период, и настроил его автономную работу через crontab. Для визуализации собранных данных я написал скрипт дашборда с несколькими фильтрами и также запустил его на удаленной машине. По результатам была подготовлена презентация с полученными графиками.  

Навыки: Python, SQLAlchemy, PostgreSQL, dash, Tableau, продуктовые метрики, построение дашбордов

[**10. Анализ рекламных источников**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-Data-Analysis/tree/main/10.%20Финальный%20проект)

Задача: 

* Проанализировать поведения игроков в зависимости от источника перехода.
* Провести исследовательский анализ данных;
* Проанализировать влияние источника перехода в игру на поведение пользователя;
* Проверить статистические гипотезы:
* Проверить гипотезу: время завершения уровня различается в зависимости способа прохождения

Описание работы: Загрузил данные и подготовил их к анализу, провел исследовательский анализ данных, проанализовал влияние источника перехода в игру на поведение пользователя. Проверил две статистические гипотезы:
* время завершения уровня различается в зависимости способа прохождения, количество построенных, 
* строений пользователем различается в зависимости источника рекламы. По результатам была подготовлена презентация с полученными графиками и дашборд.
  
Навыки: Python, EDA, статистические гипотезы, продуктовые метрики, построение дашбордов в Tableau
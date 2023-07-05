# [Анализ поведения пользователей мобильного приложения](https://github.com/Alena181/user_behavior_app/blob/194ba25396bf3c3646d0c2fe604b5a4cfbb6a384/9.%20user_behavior.ipynb)

## Задача

Необходимо проанализировать поведение покупателей на основании логов пользователей и результатов А/А/В - эксперимента (изменение шрифта во всем приложении).

## Данные

Логи пользователей мабильного приложения (файл logs_exp.csv)

название события;
уникальный идентификатор пользователя;
время события;
номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Стек

Python, А/В-тестирование, pandas, numpy, matplotlib, seaborn, scipy, plotly, продуктовые метрики, событийная аналитика



* В данном проекте мной были изучены принципы событийной аналитики. Я построила воронку продаж, исследовала путь пользователей до покупки. Проанализировала
результаты A/B-теста введения новых шрифтов. Сравнила 2 контрольных группы между собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой
Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.

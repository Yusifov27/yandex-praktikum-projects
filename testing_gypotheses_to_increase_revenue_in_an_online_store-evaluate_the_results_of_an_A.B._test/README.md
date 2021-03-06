#  Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста


## Задача
Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами

## Выводы
Топ-5 гипотез:
- Добавить форму подписки на все основные страницы, чтобы собрать базу клиентов для email-рассылок(112)
- Добавить блоки рекомендаций товаров на сайт интернет магазина, чтобы повысить конверсию и средний чек заказа(56)
- Добавить два новых канала привлечения трафика, что позволит привлекать на 30% больше пользователей(40)
- Показать на главной странице баннеры с актуальными акциями и распродажами, чтобы увеличить конверсию(40)
- Запустить акцию, дающую скидку на товар в день рождения(16.2)

В ходе анализа A/B теста было выявлено:

- Кумулятивная выручка почти равномерно растет в течении всего времени
- Средний чек имеет колбеания вначале как в группе A, так и B, и становится более стабильным в конце анализа, при том
- Есть аномальные значения
- Конверсия группы B больше конверсия A со временем, хотя изначально группа A имела большую конверсию
- Аномальные значения заказов те, которые больше 2
- Аномальныя значения стоимости заказов те, которые свыше 28000 рублей
- Нулевая гипотеза о значительных различиях в конверсии между группами по «сырым» данным была отвергнута. Относительный прирост конверсии группы B к конверсии группы A составляет 13.8 %.
- Нулевую гипотезу о значительной разнице в средних чеках между группами по «сырым» данным не отвергаем. Относительное различие среднего чека между сегментами составляет 25.9%.
- Нулевая гипотеза о значительных различиях в конверсии между группами по «очищенным» данным была отвергнута. Сегмент B значительно лучше A на 17.3%.
- Нулевую гипотезу о значительной разнице в средних чеках между группами по «очищенным» данным не отвергаем. группа B имеет средний чек ниже группы A, ниже на 2%.
- 
## Используемые библиотеки
A/B-тестирование, Matplotlib, Pandas, Python, SciPy

## Статус проекта
Завершен

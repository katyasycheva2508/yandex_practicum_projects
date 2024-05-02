# Анализ поведения пользователй мобильного приложения магазина продуктов питания
## Описание проекта
У нас есть стартап, который продаёт продукты питания.  
**Цель исследования:** изучить, как ведут себя пользователи нашего мобильного приложения. \
**Задачи исследования**
1. Изучить воронку продаж. Выяснить, как пользователи доходят до покупки, сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах. Определить эти шаги.
2. Исследовать результаты A/A/B-эксперимента. Суть эксперимента: дизайнеры захотели поменять шрифты во всём приложении, а менеджеры боятся, что пользователям будет непривычно. Поэтому решение будет приниматься по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Необходимо выяснить, какой шрифт лучше.

**Описание данных**\
Каждая запись в логе — это действие пользователя, или событие. \
EventName — название события;\
DeviceIDHash — уникальный идентификатор пользователя;\
EventTimestamp — время события;\
ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
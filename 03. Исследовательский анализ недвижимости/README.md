   # Исследование объявлений о продаже квартир

**Входные данные**: архив объявлений сервиса Яндекс.Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет в виде таблицы scv. 

**Цель**: 
установить параметры, определив рыночную стоимость объектов недвижимости. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

**Результат проекта**:
В ходе работы было выявлено большое количество пропущенных значений. По возможности заполнили данные средним значением, остальные пропуски оставили без изменений, чтобы не исказить статистику. Отсортировали данные от редких и аномальных значений Для более детального анализа рассчитали среднюю стоимость квадратного метра жилья, стоимость каждого километра удаления от центра, выделили сегмент квартир, расположенных в центре и проанализировали их параметры, а так же вывели статистику по скорости продажи объявления с даты его размещения, факторы влияющие на это и проанализировали статистику продаж в зависимости от периода размещения объявления. Для визуализации использовали графики и диаграммы.

Выявили при помощи диаграммы размаха, что нормальные значения продажи квартир варьируются от 1 до 510 дней. Но стоит обратить внимание на «быстрые» сделки, ведь в среднем по рынку продажи занимают времени от 30 дней. Определили, что на стоимость квадратного метра квартиры больше всего влияют общая площадь, жилая и кухонная зона, количество комнат, этаж квартиры, близость к центру. Большей популярностью пользуются одно- и двухкомнатные квартиры с высотой потолка от 2,65м.
***
**Статус проекта**
Завершен
***
**В проекте был применен следующий стек**
Python, Pandas, Matplotlib, исследовательский анализ данных, визуализация данных, предобработка данных, math



**Исследование объявлений о продаже квартир**

В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

**Цель исследования:**

Определить рыночную стоимость объектов недвижимости.
Построить автоматизированную систему, которая отследит аномалии и мошенническую деятельность.
Установить, какие факторы влияют на ценообразование стоимости квартир.

**Общий вывод**

Данные о продаже квартир в Санкт-Петербурге и Ленинградской области были обработаны и изучены.

В ходе изучения данных и были выявлены следующие закономерности:
- Продажа квартиры занимает в среднем от 105 до 127 дней, это 3,5 - 4 мес. Быстрыми продажами можно считать те, которые продаются в течение 1,5 мес. Долгими - все, что висят в продаже свыше 5 мес (160 дней).
- Больше всего квартр выставляется на продажу в феврале-марте и в будни (со вторника по пятницу).
- Больше всего влияют на общую (полную) стоимость объекта общая и жилая площадь. Чем они больше, тем выше цена.
- Наиболее конкурентный рынок (наибольшее количество объявлений о продаже квартир за исследуемый период) в населенных пунктах: Санкт-Петербург, Мурино, Шушары, Всеволожск, Колпино, Пушкин, Гатчина, Парголово, Кудрово, Выборг. Среди них в Выборге - самые дешевые квартиры, в Питере - самые дорогие.
- Чем ближе к центру города, тем выше цена квадратного метра

По качеству данных есть следующие рекомендации: 
- Пропуски в kitchen_area дублируют пропуски в living_area. Похоже на технический сбой при выгрузке данных.

Чтобы достичь поставленных целей, исследование проводилось в 7 этапов:
- общий обзор данных
- предобработка данных
- расчеты и добавление результатов в таблицу
- проведение анализа для Ленинградской области
- проведение анализа для Санкт-Петербурга
- определение факторов, влияющих на ценообразование стоимости квартир
- написание общего вывода

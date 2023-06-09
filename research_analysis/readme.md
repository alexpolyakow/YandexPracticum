## Исследование объявлений о продаже квартир



**Задача**   

Выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости.

**Описание проекта**

В распоряжении данные сервиса Яндекс Недвижимость — архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах.
О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. 


**Выводы**  
Подводя итог о проделаннной работе можно сказать, что было очень много пропусков в данных.

Часть из них можно было заменить медианном значением, некоторые просто заменить на -1 для удаления ошибок при анализе, часть отбросить как аномальные. Большинство квартир с большей стоимость преобладает в СПБ по отношению к другим районам. Дороже всего квадратный метр в Санкт-Петербурге - 112109.95 Дешевле всего квадратный метр в Выборге - 58315.36 Факторы влиящие на стоимость: цена, далее площадь и удаленность от значимых мест. Преобладают 1-2 и 3х комнатнные квартры как ликвидные недвижемости.Видимо их проше продать или сдать в аренду. Стоимость квадратного метра преобладает до 100 тыс. Большой спроc на кухни площадью от 5 до 20 м2. Чем ближе к центру, тем дороже квартира, как и в большенстве регионов Росиии. Спрос на покупку квартиры падает, видимо с падением спроса на дорогое и ликвидное жилье. Спрос преобладает на квартиры, располагающиеся на последнем этажах или либом другом, кроме первого этажа.(закон риелторов: не первый и в крайнем случае последний)

**Навыки и инструменты**  


Python, Pandas,  Matplotlib


Исследовательский анализ, визуализация данных, предобработка данных 

# Исследование объявлений о продаже квартир
## Данные
В проекте анализируются данные архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах от сервиса Яндекc.Недвижимость:

- Расстояние до ближайшего аэропорта в метрах (м)
- Число балконов
- Высота потолков (м)
- Расстояние до центра города (м)
- Сколько дней было размещено объявление (от публикации до снятия)
- Дата публикации
- Этаж
- Всего этажей в доме
- Апартаменты (булев тип)
- Площадь кухни в квадратных метрах (м²)
- Цена на момент снятия с публикации
- Жилая площадь в квадратных метрах (м²)
- Название населённого пункта
- Свободная планировка (булев тип)
- Число парков в радиусе 3 км
- Расстояние до ближайшего парка (м)
- Число водоёмов в радиусе 3 км
- Расстояние до ближайшего водоёма (м)
- Число комнат
- Квартира-студия (булев тип)
- Общая площадь квартиры в квадратных метрах (м²)
- Число фотографий квартиры в объявлении

## Задача
Установить параметры, которые влияют на рыночную стоимость объектов недвижимости. 

## Ход исследования
1. Изучение данных из файла.
 2. Предобработка данных.
 3. Расчёты и добавление результатов в таблицу
 4. Общий вывод.
 
 ## Итоги исследования
1. Медианное время продажи квартиры - 95 дней, среднее время продажи - 180 дней, превышение среднего над медианным почти в 2 раза вызвано выбросами;
2. Квартиры с более высокой стоимотью (обусловленной как большей площадью, так и большей ценой квадратного метра) продаются дольше;
3. Зависимость стоимости квадратного метра от площади квартиры, числа комнат, даты публикации практически отсутствует как для всей выборки, так и для квартир в центре;
4. Зависимость стоимости квадратного метра от удаленности от центра отрицательная, выражена слабо;
5. Самая низкая стоимость квадратного метра у квартир на 1 этаже, далее идут квартиры на последнем этаже, а самые дорогие - на остальных этажах;
6. Квартиры в Санкт-Петербурге дороже, чем в других населенных пунктах; следом идут квартиры в населенных пунктах Ленинградской области, расположенных в непосредственной близости от метро; самая низкая стоимость в удаленных населенных пунктах Ленинградской области.
7. При удалении от центра стоимость квадратного метра падает; к центральной области относятся квартиры на удалении до 7 км от центра; есть пояс около 20 км от центра с более дорогой недвижимостью (очевидно, коттеджные поселки).

Рекомендации:

- уделить больше внимания автоматическому заполнению данных по расстоянию до парков и водоемов, чтоб было меньше пропусков;
- сделать обязательным для заполнения поле про статус апартаментов;
- добавить проверку заполненного значения высоты потолков.

## Используемые библиотеки
- Pandas
- Matplotlib

## Статус
Проект завершен

# Исследование рынка общественного питания Москвы
## Данные
Открытые данные о заведениях общественного питания Москвы

- Название заведения
- Адрес заведения
- Категория заведения, например «кафе», «пиццерия» или «кофейня»
- Информация о днях и часах работы
- Широта географической точки, в которой находится заведение
- Долгота географической точки, в которой находится заведение
- Рейтинг заведения по оценкам пользователей в Яндекс Картах (высшая оценка — 5.0)
- Категория цен в заведении, например «средние», «ниже среднего», «выше среднего» и так далее
- Строка, которая хранит среднюю стоимость заказа
- Число с оценкой среднего чека, которое указано только для значений из столбца avg_bill, начинающихся с подстроки «Средний счёт»
- Число с оценкой одной чашки капучино, которое указано только для значений из столбца avg_bill, начинающихся с подстроки «Цена одной чашки капучино»
- Число, выраженное 0 или 1, которое показывает, является ли заведение сетевым (для маленьких сетей могут встречаться ошибки)
- Административный район, в котором находится заведение, например Центральный административный округ
- Количество посадочных мест

## Задача
- провести исследование рынка общественного питания Москвы;
- дать рекомендации по открытию ресторана с официаетами-роботами;
- подготовить презентацию для инвесторов.

## Ход исследования
 1. Изучение данных из файлов.
 2. Предобработка данных.
 3. Анализ данных.
 4. Вывод.
 
## Итоги исследования
- оптимальным форматом для выбранной концепции заведения будет ресторан - этот формат является третьим по распространенности; вариант, находящийсяя на первом месте - кафе - подходит в меньшей степени; третье место занимают столовые - этот формат для выбранной концепции не подходит совсем;

- большинство заведений в Москве несетевые, однако среди ресторанов сетевых 23% - в целом, выбранный формат можно рассматривать для развития небольшой сети, с количеством точек до 5 шт., т.к. оригинальная идея выделит рестораны среди конкурентов;

- самый распространенный вариант сетей "мало заведений / мало посадочных мест" - можно ориентироваться на него; завдения сетей такого формата рассчитаны на количество посадочных мест до 60, при этом среднее количество мест в ресторанах 96. Можно оиентироваться на диапазон от 60 до 100 мест в зависимости от площади рассматриваемых вариантов;

- центральные районы насыщены заведениями общепита, в то же время в спальных районах не будет достаточной проходимости для данного формата - для размещения стоит выбрать районы, находящиеся в центре, но на не самых оживленных улицах - аренда там будет ниже, а ради интересного опыта клиенты будут готовы потратить чуть больше времени на дорогу.
 
 ##  Ссылка на презентацию
 https://drive.google.com/file/d/1xlGFDZqMkBfTWvyugrdhfRby7c4z9Q2G/view?usp=share_link
 
 ## Используемые библиотеки
- Pandas
- Seaborn
- Plotly
- Визуализация данных

## Статус
Проект завершен

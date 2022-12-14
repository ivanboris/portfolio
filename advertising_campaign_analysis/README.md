# Анализ эффективности маркетинговых мероприятий развлекательного приложения
## Данные
Лог сервера с данными о посещениях приложения новыми пользователями, зарегистрировавшимися в период с 2019-05-01 по 2019-10-27, выгрузка их покупок за этот период, а также статистика рекламных расходов.

## Задача
Провести анализ рекламных кампаний и выявить неэффективные каналы привлечения.

## Ход исследования
 1. Изучение данных.
 2. Предобработка данных.
 3. Добавление функций для расчета и анализа LTV, ROI, удержания и конверсии.
 4. Исследовательский анализ данных.
 5. Маркетинг.
 6. Оценка окупаемости рекламы для привлечения пользователей.
 7. Выводы.
 
## Итоги исследования

**Причины неэффективности рекламы:**
1. Пользователи из США стабильно не окупаются из-за низкого уровня удержания.
2. Реклама стабильно не окупается на iPhone, Mac и Android. Реклама на PC окупается благодаря чуть более высокому уровню удержания.
3. Реклама из трех источников стабильно не окупается - это TipTop, FaceBoom, AdNonSense. При этом рекламные расходы на каналы TipTop и FaceBoom в сумме составляют более 85% от всех расходов на рекламу. Пользователи из FaceBoom, AdNonSense не окупаются из-за низкого уровня удержания; пользователи TipTop не окупаются из-за возросшей стоимости клика.

**Рекомендации для отдела маркетинга для повышения эффективности:**
1. Проанализировать рекламные расходы на регион США. При том, что покупатели из этого региона не окупаются, в США самое лучшее соотношение платящих клиентов к их общему числу. Стоимость привлечения клиентов из этого региона резко выросла в конце мая - начале июня. Проанализировать, какие изменения привели к этому, попробовать снизить стоимость привлечения. Для этого можно распределить рекламный бюджет на другие каналы.
2. Пересмотреть рекламные расходы на канал TipTop, т.к. окупаемость клиентов из него на самом низком уровне, при этом стоимость привлечения клиентов из этого канала постоянно растет и превышает более чем в 2,5 раза стоимость привлечения из других каналов, а бюджет составляет более половины от всех рекламных расходов. Уровень удержания пользователей из этого канала такой же, как у каналов, которые окупаются. Веротяно, снижение стоимости клика позволит вывести рекламу в этом канале на окупаемость. По соотношению платящих клиентов к общему числу этот канал на 4 месте.
3. Обратить внимание на каналы FaceBoom, AdNonSense - пользователи из этих каналов так же не окупаются. При этом по доле плятящих клтентов эти каналы на 1 и 2 месте. Стомиость привлечения стабильная - можно попробовать снизить ее и вывести трафик из этих каналов в зону окупаемости.
4. Проверить работу сервиса на устройствах iPhone, Mac и Android - возможно, реклама не окупается в связи с техническими проблемами, возникающими у пользоватлей этих утройств.
5. Рассмотреть возможность увеличения бюджета на источник lambdaMediaAds - по доле платящих клиентов данный источник на 3 месте с 10.47%, стоимость клика стабильная и составляет 0,74, окупаемость наступает на 3 день. При этом рекламные расходы на него всего 1,48%.

## Используемые библиотеки
- Pandas
- Matplotlib
- Seaborn

## Статус
Проект завершен

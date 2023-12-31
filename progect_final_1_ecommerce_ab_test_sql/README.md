# E-commerce — Выявление профилей потребления
## Цель исследования
Сегментировать покупателей на основе истории их покупок. На основе сегментации покупателей сделать предложение о наилучшем рекламном предложении покупателям.

## Ход исследования
-Загрузка данных и изучение общей информации.\
-Подготовка данных.\
-Провести исследование данных.\
-Анализ покупок пользователей на основе категорий товаров.\
-Анализ покупок пользователей на основе выручки с продаж.\
-Определить сегменты на основе покупок пользователей.\
-Формулировка и проверка статистических гепотез.\
-Вывод.

## Описание исследования
Интернет-магазин товаров для дома «Пока все ещё тут». Помочь магазину стать лучше, а клиентам — обустроить дом своей мечты. Задачи — анализ товарного ассортимента и создание гипотез на основе полученных данных.

## Описание данных
Датасет описывает транзакции интернет-магазина товаров для дома и быта «Пока все ещё тут».\
Колонки в `ecommerce_dataset.csv`:\
`date` — дата заказа;\
`customer_id` — идентификатор покупателя;\
`order_id` — идентификатор заказа;\
`product` — наименование товара;\
`quantity`— количество товара в заказе;\
`price` — цена товара.
## Итоги исследования
В ходе исследования был проанализирован датасет интернет-магазин товаров для дома «Пока все ещё тут».

В исследовании мы проанализировали показатели продаж магазина. Покупатели в основном делают один заказ и больше в магазин не возвращаются. Количество повторных заказов на одного уникального покупателя 1.45. Покупатели в основном покупают одно наименование товара, что следует из медианного количества товаров в заказе платя за него по медианноу показателю 577 у.е. Магазину стоит обратить на это внимание и начать вести работу по удержанию покупателей, проработать стимулы для увеличения повторных заказов.

Для динамики продаж по месяцам характерна сезонность, продажи достигают высоких показателей октябре и перед новым годом.

В исследовании мы разделили товары магазина на 8 категорий, определили что большую выручку приносят товары из категории хоз.товары, однако большим объемом заказов обладает категория растения. В димике по месяца наблюдаем, что категория хоз.товары приносит большую часть выручки с октября по декабрь, а в течении остальной части года обладает стабильным средним объемом выручки. Категория растения в разрезе выручки подвержена влиянию сезонности выручка по ней начинает расти с апреля по июнь. По объему заказов категория растения в течении всего года обладает большим объемом, исключая месяцы с июля по сентябрь.

Было выделено 6 кластеров 0,1,2,3,4,5. В кластер 0 попали основная масса покупателей. Покупают большую часть категорий товаров, но количество закзов в среднем составляет 1.81, средний чек 935.77. В 1 кластер попал постоянный клиент который долгое время покупает товары в разных категориях, обладает самой высокой накопленной выручкой. В кластер 2 попал всего один покупатель совершивший единоразовую, крупную покупку в один день. В кластер 3 и 5 попали покупатели со схожим количеством заказов, в категории 5 выше средний чек. В кластер 4 попали покупатели предпочитающие категорию товаров "растения". Заказы делают часто, но средний чек составляет 140.33. Для магазина будет выгодно увеличить состав кластера 1.

Следующим этапом анализа была проверка двух гипотез:

средняя стоимость заказа в категории товаров растения кластера 0 и 4 одинаковы.
средняя стоимость заказа в категориях товаров хоз. товары и растения одинаковы.
Обе нулевые гипотезы были отвергнуты.

### Рекомендации:

- Проработать программу лояльности покупателей, которая побудит клиента сделать еще один заказ, а в дальнейшем превратиться в постоянного покупателя. Например, ввести баллы лояльности.
- Разработать программу привлечения новых клиентов для кластера 0, в нем высока доля покупок товаров из категории хоз.товары которые приносят ощутимую долю всей выручки.
- Проработать акции для увеличения продаж в рамках покупателей товаров наиболее перспективных категорий товаров, предлагать к продаже к покупаемому товару товар из тойже категории по акционной цене.

# SnaksSales

Визуализация данных о продажах снеков в период с сентября 2021 по середину декабря 2021 в 14 городах России

Показывает выручку и количество проданых товаров по городам, недельную сезонность продаж по категориям товаров, долю выручки каждой категории, количество распроданных товаров, топ 5 товаров по выручке, по категориям и зависимость их продаж от средней цены 

#### Категории
Товары разделены по ценовым категориям:
- Economy
- Middle
- Plus
- Premium

##### Определение категории товара
Товары определены по категориям в зависимости от средней цены по городу:
- Economy: Средняя цена находится в диапазоне от минимальной до 25-го перцентиля всех цен
- Middle: Средняя цена находится в диапазоне от 25-го перцентиля до  50-го перцентиля всех цен
- Plus: Средняя цена находится в диапазоне от 50-го перцентиля до  75-го перцентиля всех цен
- Premium: Средняя цена находится выше 75-го перцентиля всех цен

* Определение товара в категорию может быть улучшено использованием цены товара за единицу веса/объема вместо цены товара

### Выводы
- Наблюдается недельная сезонность с пиком в субботу, самые большие пики в понедельник и вторник. День с наибольшей выручкой - вторник
- Наибольшую выручку приносят товары категории Plus, наименьшую - товары категории Economy
- На графиках зависимости продаж топ 5 товаров по выручке от их средней цены можно увидеть, что количество проданых товаров растет с уменьшением цены. Однако это справедливо не для всех товаров и эта гепотеза требует более подробного изучения

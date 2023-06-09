# Ритейл — Анализ программы лояльности

Оценка эффективности торговых точек.  
Магазин «Строили, строили и наконец построили» занимается продажей строительных материалов. Все покупатели могут получить доступ в магазин с использованием персональных карт. За 200 рублей в месяц они могут стать участниками программы лояльности. В программу включены скидки, специальные предложения, подарки.

**Цель исследования:** оценить эффективность магазинов сети.

**Задачи исследования:**

- провести исследовательский анализ данных;
- оценить эффективность;
- сформулировать и проверить статистические гипотезы.

**Исходные данные:** данные о покупках в магазинах сети за период с 01.12.2016 по 28.02.2017.

**Описание исходных данных:**

файл retail_dataset.csv содержит данные о покупках в магазине:

- `purchaseId` — id чека;
- `item_ID — id` товара;
- `purchasedate` — дата покупки;
- `Quantity` — количество товара;
- `CustomerID` — id покупателя;
- `ShopID` — id магазина;
- `loyalty_program` — участвует ли покупатель в программе лояльности;

файл product_codes.csv содержит данные о стоимости одной единицы товара:

- `productID` — id товара;
- `price_per_one` — стоимость одной единицы товара.


**План работы:**

1. Обзор исходных данных
2. Предобработка данных
3. Исследовательский анализ данных
   - Объединим датасеты
   - Добавим столюбцы
   - Исследуем распределение количества покупок по дням, неделям, месяцам
   - Исследуем средние значения покупки, глубины чека и частоты покупок между клиентами участвующими и не участвующими в программе лояльности
   - Исследуем средние значения покупки, глубины чека и частоты покупок между клиентами участвующими и не участвующими в программе лояльности только для магазина `Shop 0`
   - Добавим недельные срезы и анализ относительных метрик от среднего чека, средней глубины чека и т.д.
   - Исследуем распределения количества уникальных покупателей
   - Исследуем суммарную выручку в локациях
   - Исследуем соотношение количества покупателей и выручки в локациях
   - Исследуем распределение покупателей из разных категорий в локациях
4. Проверка гипотез
   - Гипотеза о средних значениях покупки, глубины чека и частоты покупок между клиентами участвующими и не участвующими в программе лояльности
   - Гипотеза о средних значениях покупки, глубины чека и частоты покупок между клиентами участвующими и не участвующими в программе лояльности магазина `Shop 0`.
5. Выводы
   - Формулирование выводов по результатам исследования
6. Дашборд и презентация
   - Оформление дашборда
   - Оформление презентации


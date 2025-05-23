# Ads CTR Forecasting
Анализ CTR рекламы означает анализ кликабельности для рекламы. Анализ CTR рекламы — это процесс проверки эффективности интернет-рекламы путем измерения скорости, с которой пользователи нажимают на ссылку рекламы, чтобы попасть на сайт рекламодателя.<p>
Анализ и прогнозирование CTR объявлений имеют решающее значение для компаний, чтобы оценить окупаемость инвестиций (ROI) в свои рекламные усилия и принимать решения на основе данных для улучшения эффективности рекламы.<p>
Задачи анализа и прогнозирования CTR объявлений:
- Собрать данные о рекламе, включая количество показов рекламы (как часто показывалось объявление), количество кликов и любые другие соответствующие показатели.
- Изучить данные, чтобы понять их характеристики и распределение. Рассчитать основные статистические данные, такие как средний CTR (рейтинг кликов) и стандартное отклонение.
- Создать визуализации, такие как линейные диаграммы или столбчатые диаграммы, для представления тенденций CTR с течением времени.
- При необходимости провести A/B-тесты, чтобы сравнить эффективность различных вариантов рекламы.
- Проанализировать данные CTR, чтобы определить факторы, влияющие на эффективность рекламы.
- Построить модель прогнозирования для прогнозирования будущих значений CTR.<p>
  [Датасет:](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/ctr.csv)
-  Дата: дата, на которую были записаны данные.
- Клики: количество кликов пользователей по рекламе.
- Показы: общее количество показов рекламы пользователям.
# Визуализация кликов и показов
![Click and Impressions Over Time](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/Clicks%20and%20Impressions%20Over%20Time.png)
# Pассмотрим взаимосвязь между кликами и показами:
![Relationship Between Clicks and Impressions](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/Relationship%20Between%20Clicks%20and%20Impressions.png)<p>
Итак, связь между кликами и показами линейна. Это означает, что более высокие показы рекламы приводят к более высоким кликам по рекламе. <p>
# Посчитаем и визуализируем CTR с течением времени:
![Click-Through Rate (CTR) Over Time](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/Click-Through%20Rate%20(CTR)%20Over%20Time.png)
# Посмотрим на средний CTR по дням недели:
![Average CTR by Day of the Week](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/Average%20CTR%20by%20Day%20of%20the%20Week.png)
# Сравним CTR в будни и выходные:
![Comparison of CTR on Weekdays vs. Weekends](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/Comparison%20of%20CTR%20on%20Weekdays%20vs.%20Weekends.png)
# Cравним показы и клики по будням и выходным:
![Impressions and Clicks on Weekdays vs. Weekends](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/Impressions%20and%20Clicks%20on%20Weekdays%20vs.%20Weekends.png)<p>
Теперь давайте посмотрим, как спрогнозировать CTR рекламы. Поскольку CTR зависит от показов, а показы меняются со временем, мы можем использовать методы прогнозирования временных рядов для прогнозирования CTR. Поскольку CTR является сезонным, давайте рассчитаем значения p, d и q для модели SARIMA:<p>
![acf_pacf_plot](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/acf_pacf_plot.png)
# Bизуализируем прогнозируемую тенденцию CTR:
![CTR Forecasting](https://github.com/Mamaeva-Bariyat/Ads-CTR-Forecasting/blob/main/Images/CTR%20Forecasting.png)







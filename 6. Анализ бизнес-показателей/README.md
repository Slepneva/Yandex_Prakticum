# Тема: Анализ бизнес-показателей
# Проект: Анализ источников трафика и перераспределение бюджета отдела маркетинговой аналитики Яндекс.Афиши

#### Описание
По данным Яндекс.Афиши необходимо определить невыгодные источников трафика и перераспределить бюджет для дальнейших маркетинговых кампаний.

#### Используемые инструменты и методы
* изучение общей информации о данных: head(), info(), describe()
* замена типов данных: astype()
* обработка дубликатов: duplicated()
* анализ данных: groupby(), sort_values(), mode(), join(), merge(), pivot_table(), cumsum()
* построение графиков: plot(), plot(kind='bar'), hist(), heatmap()

#### Краткий вывод
***Итоги аналитики***
ROMI показал, что единственный источник трафика по которому ни одна когорта не окупила затраты - это 3. Cледует обратить внимание на 1 и 9 источники трафика, вероятно необходимо провести акцию для подогрева покупателей. По 4 и 5 следует проводить акции перед большими праздниками. 2, 3 и 10 источники пока оставить под наблюдением за поведением покупателей

***Итоги показателей метрик***
По графикам показателей можно заметить пики и спады прихода новых пользователей, которые могут говорить о результатах проведенных маркетинговых компаний, о праздниках и о возможных сбоях в работе сервиса. Retention Rate (коэфициент возвращаемости покупателя) в первую неделю убывает по когортам с течением времени. 
Наибольшее количество пользователей совершают покупку в первые дни с момента первого посещения сайта, а чаще всего покупка происходит в течение 1 минуты. В среднем за полгода покупатель совершает 1 покупку на сумму от 3.42 до 5.85 условных единиц.
Самые большие траты были сделаны на маркетинг для 3 источника трафика, а самые маленькие траты на источник 9. По времени самые большие траты были сделаны в предновогоднюю маркетинговую компанию. Средний CAC на одного покупателя для всего проекта равняется 9.31, что является достаточно высоким показателем. Наибольшие затраты на привлечение одного покупателя замечены в августе

***Итоги когортного анализа***
В разрезе когорт в рамках когортного анализа были рассматрены такие метрики как Retention Rate, LTV, CAC и ROMI, подробнее о результатах в прокте. 

Если файл .ipynb не прогружается, воспользуйтесь [ссылкой](https://nbviewer.jupyter.org/github/Slepneva/Yandex_Prakticum/blob/main/6.%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81-%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B8%D1%81%D1%82%D0%BE%D1%87%D0%BD%D0%B8%D0%BA%D0%BE%D0%B2%20%D1%82%D1%80%D0%B0%D1%84%D0%B8%D0%BA%D0%B0%20%D0%B8%20%D0%BF%D0%B5%D1%80%D0%B5%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B1%D1%8E%D0%B4%D0%B6%D0%B5%D1%82%D0%B0%20%D0%BE%D1%82%D0%B4%D0%B5%D0%BB%D0%B0%20%D0%BC%D0%B0%D1%80%D0%BA%D0%B5%D1%82%D0%B8%D0%BD%D0%B3%D0%BE%D0%B2%D0%BE%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B8%20%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81.%D0%90%D1%84%D0%B8%D1%88%D0%B8.ipynb) ресурса nbviewer.jupyter.org, желательно не в браузере Google Chrome (например, Microsoft Edge)
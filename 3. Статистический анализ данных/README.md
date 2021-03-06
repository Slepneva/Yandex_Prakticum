# Тема: Статистический анализ данных
# Проект: Определение перспективного тарифа для телеком компании

#### Описание
По данным пользователей телеком компании необходимо определить наиболее выгодный для компании Тариф для его дальнейшего развития

#### Используемые инструменты и методы
* изучение общей информации о данных: head(), info(), describe()
* обработка пропущенных значений: isna()
* замена типов данных: astype(), to_datetime()
* подготовка к данных анализу: groupby(), merge()
* построение графиков: boxplot(), plot(kind='hist')
* проверка гипотез: st.ttest_ind()

#### Краткий вывод
Лучшим тарифом является Smart, так как он наиболее подходит по параметрам под потребности пользователей. Но со стороны увеличения выручки лучшим тарифом является Ultra, так как за меньшее количество потраченного пакета пользователь платит больше практически в 4 раза.

Если файл .ipynb не прогружается, воспользуйтесь [ссылкой](https://nbviewer.jupyter.org/github/Slepneva/Yandex_Prakticum/blob/main/3.%20%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%B5%D1%80%D1%81%D0%BF%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D0%BB%D0%B5%D0%BA%D0%BE%D0%BC%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8.ipynb) ресурса nbviewer.jupyter.org, желательно не в браузере Google Chrome (например, Microsoft Edge)
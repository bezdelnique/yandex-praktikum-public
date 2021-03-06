# Яндекс.Практикум (Data Scientist)
Период обучения октябрь 2019 - июль 2020.

Программа курса: https://praktikum.yandex.ru/data-scientist


## Реализованные проекты

- Разработал методику планирования рекламной кампании для интернет-магазина игр. Для подтверждения использовал проверку гипотезы о равенстве средних
- Бурение скважин. Определил порог безубыточности методом Bootstrap используя для подтверждения гипотезы 95% доверительный интервал
- Построил модель оттока клиентов банка. Модель RandomForestClassifier, метрика f1 мера
- Построил модель предсказания коэффициента восстановления золота из золотосодержащей руды. Модель LinearRegression, метрики: sMAPE и MAE
- Реализовал защиту данных клиентов страховой компании. Использовал умножение признаков на обратимую матрицу и учил модель на них. Для подтверждения верности предсказаний использовал гипотезу о равенстве средних
- Реализовал алгоритм модели линейной регрессии методом стохастического градиентного спуска
- Разработал модель предсказания рыночной стоимости автомобиля на основе исторических данных. Модель CatBoostRegressor, метрика RMSE
- Спрогнозировал количество заказов такси на следующий час. Модель RandomForestRegressor, метрика RMSE
- Сделал анализ тональности отзывов. Подготовка признаков: TfidfVectorizer\ SnowballStemmer, модель LogisticRegression, метрика F1 мера
- Реализовал модель распознавания изображения фруктов. Нейросеть на backbone ResNet50, метрика MAE
- Спрогнозировал отток оператора связи. Модель CatBoostClassifier, метрика ROC-AUC, accuracy.


## Используемые технологии и подходы
### Библиотеки
- Pandas 
- Numpy 
- Matplotlib 
- Seaborn
- Scikit-learn 
- Keras
- Catboost

### Изучил подходы и методы
- Статистический анализ данных
- Реализация регрессионных, бинарных, категориальных моделей предсказаний
- Компьютерное зрение 
- NLP
- Анализ и прогнозирование временных рядов
- Кластеризация и поиск аномалий	

## Работы для озакомления

* [Предсказание оттока клиентов мобильного оператора (выпускная работа)](MobileOperatorChurn)
* [Система определеяет рыночную стоимость подержанного авто](SaleCarPrice)
* [Оптимизация работы перевозчика. Прогноз количества заказов такси на следующий час](TaxiOrderAmount)
* [Определение токсичности комментариев пользователей](WikiEditToxicComment)


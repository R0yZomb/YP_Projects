### Hi, i'm Data Scientis 

### Nabatnikov Denis / Набатников Денис

Telegram: t.me/@R0y_zomb

Email: r0yjank1ns@gmail.com

В этом репозитории собраны мои проекты из курса "Специалист по Data Science" Яндекс.Практикума
(Here you'll find my projects from the "Data Science Specialist" training program by Yandex.Praktikum)

Краткое описание проектов и ссылки:
| |Название|Краткое описание|Инструменты|Что сделано|
|--|----|----|-|----|
|1.| [Анализ игровой индустрии] | Исследование продаж компьютерных игр в различных регионах и определение стратегии рекламной компании| `pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib` | Проведен анализ данных о продажах игр по всему миру начиная с 80-х годов. Определены пики популярности и периоды жизни игровых консолей, а также самые популярные кроссплатформенные игры. Проведен анализ корреляции мнения критиков, журналистов и пользователей с реальными продажами. Составлены портреты клиентов по странам с предпочтениями к платформам, жанрам, конкретным продуктам. Проверены гипотезы о самых популярных жанрах и платформах. |
|2.| [Предсказание прибыли нефтедобывающей компании] | Модель предсказаний прибыли компании и выбор прибыльных регионов для разработки нефти| `pandas`, `numpy`, `matplotlib`, `scipy`, `sklearn` |В избранном регионе собраны характеристики для скважин: качество нефти и объём её запасов. Построена модель для предсказания объёма запасов в новых скважинах, использована LinearRegression с метрикой RMSE. Определены скважины с самыми высокими оценками значений добычи. Рассчитаны точки безубыточности, риски убытков, выбран регион с максимальной суммарной прибылью отобранных скважин.|
|3.| [Предсказание выработки золотодобывающей компании] | Модель предсказания качества очистки золотоносной руды| `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, `sklearn` | Проведен анализ корректности расчета исходной эффективности обогащения сырья. Выявлены аномалии в техпроцессе, данные очищены от выбросов. Найдены параметры концентрации металлов на всех этапах очистки, определено влияние размера гранул сырья на процесс обогащения и выхода продукта. Предсказаны параметры процесса по данным о сырье. Использовались: LinearRegression, RandomForestRegressor, Lasso c метрикой SMAPE на кроссвалидации, а также проверкой на константной и Dummy модели.|
|4.| [Временные ряды для предсказания количества заказов такси] | Модель предсказания заказов такси на следующий час |`pandas`, `numpy`, `statsmodel`, `matplotlib`, `sklearn`,`scipy`, `xgboost`, `catboost`, `seaborn`| Проведен анализ времнного ряда по дням в рамках года, определен тренд и сезонность в течении недели и дня. Собрана модель для предсказания на несколько часов вперед в течении дня. Тестировались  SARIMA, XGBoost, CatBoost, GradientBoostingRegressor, LinearRegression метрикой RMSE.|

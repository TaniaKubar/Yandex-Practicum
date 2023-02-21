# Репозиторий учебных проектов Яндекс.Практикум по направлению "Специалист по Data Science" 
| Название проекта | Описание | Используемые библиотеки |
| :---------: | :--------------------- |:--------------|
|[1. Исследование надежности заемщиков](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/1_creditworthiness_research)| На основе данных кредитного отдела банка исследовано влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на четыре.| *pandas pymystem3 collections*
|[2. Исследование рынка недвижимости в Санкт-Петербурге и соседних населённых пунктах](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/2_real_estate_research)| На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания, матрица корреляции.| *pandas numpy matplotlib seaborn*
|[3. Исследование рынка российского кинопроката](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/3_film_distribution_research)| На основе данных о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информации с сайта КиноПоиск изучен рынок российского кинопроката и выявлены текущие тренды. Сделан анализ того, насколько  фильмы, которые получили государственную поддержку, интересны зрителю. | *pandas matplotlib seaborn*
|[4. Определение перспективного тарифа для телеком-компании](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/4_tariffs_research)| Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.| *pandas numpy scipy matplotlib*
|[5. Классификация клиентов телеком компании](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/5_tariffs_recomendation)| Обучены модели решающего дерева, случайного леса и логистической регрессии для классификации клиентов телекоммуникационной компании с целью рекомендации подходящего тарифа. Подобраны гиперпараметры, выбрана наилучшая модель и протестирована на отложенной выборке. | *pandas sklearn*
|[6. Пронозирование оттока клиентов банка](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/6_customers_churn_research)| Проведен предварительный анализ клиентов банка. Подготовлены признаки (OHE, scaler), выделены обучающая, валидационная и тестовая выборки. Обучены модели логистической регрессии, решающего дерева и случайного леса. Изучено влияние разных методов борьбы с дисбалансом классов. Выбрана и протестирована на отложенной выборке наилучшая модель с разными методами борьбы с дисбалансом классов. | *pandas numpy seaborn matplotlib sklearn*
|[7. Определение наиболее выгодного региона нефтедобычи](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/7_oil_well_locations_research)| Проведен обзор данных о пробах сырья в скважинах трех регионов. Подготовлены выборки для обучения и тестирования модели. Для каждого региона обучена модель линейной регрессии и сделаны предсказания объема запасов сырья. С использованием техники bootstrap рассчитан риск получения убытков для каждого региона и 95%-й доверительный интервал.| *pandas numpy scipy sklearn*
|[8. Прогнозирование оттока клиентов отеля](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/8_customers_churn_investigation)| Проведены обзор, предобработка и исследовательский анализ данных клиентов. Признаки подготовлены для обучения, выделены обучающая и тестовая выборки. Обучены модели логистической регрессии, решающего дерева и случайного леса, подобраны параметры и выбрана наилучшая по метрике f1 модель. Наилучшая модель протестирована, на основании предсказаний модели рассчитана прибыль, которую принесет модель. Проанализированы характеристики клиента, оказывающие наибольшее влияние на принятие решения модели. Выявлены признаки ненадежного клиента.| *pandas matplotlib seaborn sklearn*
|[9. Предсказание стоимости жилья](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/9_median_house_value_prediction)| Этот проект выполнен с использованием pyspark. Проведен обзор и анализ данных о жилье в Калифорнии в 1990 году. Удалены выбросы, данные разбиты на обучающую и тестовую выборки и подготовлены для обучения. Обучена модель линейной регрессии с подбором параметров и проанализирован результат. | *pandas numpy matplotlib seaborn pyspark*
|[10. Определение стоимости автомобилей](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/10_car_price_prediction)| Проведен обзор, анализ и предобработка данных о состоянии автомобилей и их технических характеристиках. Для каждой используемой модели подготовлены выборки с учетом необходимой обработки признаков. Обучены модели линейной регрессии, решающего дерева, LGBMRegressor и CatBoostRegressor, подобраны наилучшие параметры. Модели протестированы и проанализированы по качеству прогрозов и скорости работы. | *pandas numpy matplotlib seaborn sklearn lightgbm catboost*
|[11. Практика SQL](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/11_sql_practice)| В этом проекте выполнены различные запросы по выгрузке информации из базы данных. Отработаны основные функции, проведен когортный анализ. | *pandas matplotlib seaborn sqlalchemy*
|[12. Прогнозирование температуры звезды](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/12_stars_temperature_prediction)| Проведен обзор, предобработка и анализ основных характеристик звезд. Подготовлены выборки для обучения и тестирования нейронной сети. Построены нейронные сети с разной архитектурой, с помощью skorch подобраны паарметры сети. Проанализированы предсказания на тестовой выборке и проведено сравнение разных моделей. | *pandas numpy math seaborn matplotlib sklearn torch skorch*
|[13. Разработка системы предупреждения аварий на каршеринге](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/13_car_crash_prediction)| Проведен обзор, предобработка и анализ исторических данных по статистике ДТП с участием автомобилей каршеринга. Отобраны важные для обучения моделей признаки. Подготовлены выборки для обучения и тестирования разных моделей. Выбрана наилучшая модель, выявлены и проанализированы основные факторы ДПТ. | *pandas numpy seaborn matplotlib sqlalchemy sklearn lightgbm catboost*
|[14. Прогнозирование количества заказов такси](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/14_taxi_demand_prediction)| Проведен обзор и анализ данных о количестве заказов такси в разное время и даты. Оценена стационарность ряда с помощью теста Дики-Фуллера. Подготовлены выборки и обучены модели. Подобраны параметры и сгенерированы наиболее подходящие признаки. Проанализированы предсказания наилучшей модели на тестовых данных. | *pandas numpy matplotlib statsmodels sklearn lightgbm*
|[15. Определение токсичных комментариев](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/15_toxic_comments_detection)| Проект выполнен с использованием gpu. Проведены обзор и предобработка текстовых комментариев. Для сравнения сформировано два датасета - признаки полученные с помощью tf-idf и эмбеддинги, полученные с помощью предобученной модели BERT. Данные разделены на обучающую и тестовую выборки. Модели обучены на обоих вариантах датасетов и проведен анализ качества на основе метрки f1. | *pandas numpy seaborn matplotlib re spacy nltk torch transformers sklearn lightgbm*
|[16. ](https://github.com/TaniaKubar/Yandex-Practicum/tree/main/16_age_detection)||
|[]()||
|[]()||

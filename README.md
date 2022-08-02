# Репозиторий проектов по анализу данных
В этом репозитории размещены проекты, выполненные мной в **Python и его библиотеках** в ходе обучения в Яндекс.Практикуме по профессии "Аналитик данных":
|Название проекта|Описание|Используемые инструменты|Навыки
|:--------------------|:--------------------|:--------------------|:--------------------
|[Сегментация клиентов банка](Сегментация клиентов банка)|В проекте проведен анализ данных о клиентах банка с целью выявления причин большого оттока. Исследовано влиятние различных признаках на отток, выявлены ключевые признаки, которые легли в основу сегментации клиентов. Составлены портреты пользователей каждого сегмента, по высокооточным сегментам предложены рекомендации по удержанию клиентов. Проверены статистические гипотезы по вопросам исследования|python, pandas, matplotlib, seaborn, scipy|Cегментация базы по стратегическим признакам, cтатистический анализ, проверка гипотез, 
|[Анализ результатов А/В-теста, связанного с изменением рекомендательной системы на сайте](Анализ_результатов_АВ_теста)|Проведена оценка корректности проведенного А/В-теста: исследовано пересечение пользователей между группами теста и с группами конкурирующего теста, совпадение теста с другими маркетинговыми активностями. Проанализированы результаты А/В теста, подготовлены выводы и рекомендации.|python, pandas, numpy, matplotlib, skipy, proportions_ztest|A/B-тест, проверка статистических гипотез
|[Прогноз оттока и кластеризация клиентов фитнес-центра](Прогноз_оттока_и_кластеризация)|В проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей (выделены кластеры и описаны их свойства); проанализированы основные признаки, наиболее сильно влияющие на отток.|python, pandas, matplotlib, seaborn, scikit-learn, scipy|Машинное обучение, классификация, кластеризация
|[Анализ поведения пользователей мобильного приложения](Активность_в_моб_приложении)|В проекте изучены принципы событийной аналитики. Построена воронка продаж, исследован путь пользователей до покупки. Проанализированы результаты А/А/В-эксперимента по изменению внешнего вида приложения.|python, pandas, numpy, matplotlib, seaborn, plotly, scipy|Cобытийная аналитика, продуктовые метрики, A/B-тест, проверка статистических гипотез, визуализация данных
|[Исследование причин убыточности развлекательного приложения](Причины_убытков_приложения)|Проведен анализ данных от развлекательного приложения. Составлены профили пользователей, использован когортный анализ, по написанным ранее функциям рассчитаны продуктовые метрики: LTV, CAC, ROI, Retention rate, Convertion rate. Определены причины убытков.|python, pandas, numpy, matplotlib, seaborn|Профили пользователей, когортный анализ, продуктовые метрики (удержание, конверсия, LTV, CAC, ROI), визуализация метрик
|[Исследование рынка заведений общественного питания Москвы](Выход_на_рынок_общепита)|В проекте исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с выводами по результатам исследования и рекомендациями|python, pandas, numpy, matplotlib, seaborn|Визуализация данных, обработка данных, создание презентаций
|[Исследование закономерностей, определяющих успешность компьютерной игры](Успешность_компьютерной_игры)|Составлены портреты пользователей и выявлены параметры, определяющие успешность игры в разных регионах мира. Проверены статистические гипотезы, выдвинутые заказчиками. Подготовлены выводы для магазина компьютерных игр для планирования рекламных кампаний.|python, pandas, numpy, matplotlib, seaborn, skipy, stats.ttest_ind, stats.mannwhitneyu|Предобработка данных, исследовательский анализ данных, описательная статистика, визуализация данных, проверка статистических гипотез, T-тест Стьюдента, тест Манна-Уитни
|[Определение перспективного тарифа для телеком-компании](Выгодный_тариф_телеком)|Проведен анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг. Проверены гипотезы, выдвинутые заказчиками.|python, pandas, numpy, matplotlib, seaborn, skipy, stats.ttest_ind|Исследовательский анализ данных, описательная статистика, визуализация данных, проверка статистических гипотез, T-тест Стьюдента

## Прогнозирование оттока и кластеризация пользователей фитнес-клуба

**Цель проекта** - разработать рекомендации по повышению качества работы с клиентами на основе выявленных признаков, наиболее сильно влияющих на отток.

Был проведен исследовательский анализ данных, устранена проблема мультиколлинеарности некоторых признаков. Модель бинарной классификации пользователей, где целевой признак — факт оттока пользователя в следующем месяце, была обучена логистической регрессией и случайным лесом. Обе модели показали хороший результат, но метрики логистической регрессии немножечко лучше.
При помощи метода К-Means были выделены кластеры пользователей, описаны их паттерны поведения. 

В **результате** среди всех кластеров пользователей было выделено два, которые находятся в хоне риска оттока. Даны рекомендации по работе с такими клиентами.

**Библиотеки** - Pandas, Matplotlib, Seaborn, Sklearn, Scipy

**Статус проекта** - завершен
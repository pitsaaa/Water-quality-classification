# Анализ данных о пригодности воды для питья и разработка модели классификации

В данном проекте представлен анализ [датасета](https://www.kaggle.com/datasets/mssmartypants/water-quality) с химическим составом воды и ее пригодности для питья. На основе этих данных были реализованы модели машшиного обучения для решения задачи классификации.

**Навыки и инструменты:**
- Python
- Pandas
- Matplotlib
- Seaborn
- sklearn
- Различные модели машинного обучения

**Используемые модели машинного обучения:**
- Логистическая регрессия
- Метод k-ближайших соседей
- Наивный байесовский классификатор
- Градиентный бустинг
- Деревья решений
- Случайный лес
- Ансамблевый метод стекинг

## Этапы проекта

1. Загрузка данных и импорт необходимых библиотек
2. Предобработка данных: очистка от дубликатов и нулевых значений
3. Исследовательский анализ данных:
	- анализ и визуализация распределения каждого признака
	- построение корреляционной матрицы признаков
4. Подготовка данных для обучения
5. Обучение моделей машинного обучения
6. Результаты и сравнение моделей

## Результаты

После обучения всех моделей я сравнил их метрики качества:
![сравнение метрик качества моделей](results_chart.png)

Модели **Random Forest** и **Stacking Classifier** показали самые наилучшие результаты на тестируемых данных, точность 97% и F1-score 0.87, что делает их наиболее эффективными и подходящими для нашей задачи классификации.

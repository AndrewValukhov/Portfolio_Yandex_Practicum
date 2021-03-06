# Прогнозирование временных рядов

#### Цель: 
- Построение модели машинного обучения для прогнозирования количества заказов такси на следующий час.

#### Краткое описание:
- Сервису такси необходимо оптимизировать доступность водителей в критические часы. Для этого необходимо иметь модель, прогнозирующие вызовы по часам. В рамках проекта осуществлены:
1. Ресемплирование данных (от 10 минут к часу);
2. Анализ временного ряда - скользящие средние и декомпозиция;
3. Созданы новые признаки - календарные признаки, лаговые переменные.
4. Обучены разные модели, проведено сравнение качества (линейная регрессия - самая точная).

#### Используемые библиотеки:
- Python, NumPy, pandas, seaborn, Matplotlib, statsmodels, scikit-learn, LightGBM.
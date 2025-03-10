# House Prices Prediction

## Описание проекта
Этот проект был создан с целью обучения и развития навыков машинного обучения. Он основан на участии в соревновании Kaggle, проект предназначен для анализа и предсказания цен на жилье с использованием набора данных.

## Используемые библиотеки
- numpy
- pandas
- seaborn
- matplotlib
- scipy
- scikit-learn

## Описание шагов

1. **Импорт библиотек**: Импорт необходимых библиотек для анализа данных, визуализации и машинного обучения.
2. **Загрузка данных**: Загрузка обучающих и тестовых данных.
3. **Первичный анализ данных**: Просмотр первых строк и размеров датасетов, информации о столбцах.
4. **Графический анализ**: Построение графиков для визуализации данных и выявление выбросов.
5. **Обработка пропущенных данных**: Заполнение пропусков медианой и модой.
6. **Обработка категориальных данных**: Применение LabelEncoder для категориальных признаков.
7. **Нормализация данных**: Применение StandardScaler для нормализации числовых признаков.
8. **Обучение моделей**: Обучение моделей GradientBoostingRegressor, Ridge и RandomForestRegressor с использованием GridSearchCV.
9. **Оценка моделей**: Оценка моделей с помощью метрики RMSE.
10. **Формирование предсказаний**: Создание финальных предсказаний для тестового набора данных и сохранение результатов в CSV файлы.

## Полученные метрики
RMSE (Корень из средней квадратичной ошибки):

- Gradient Boosting Regressor: 0.130
- Ridge Regression: 0.125
- Random Forest Regressor: 0.149

## Структура репозитория
- **house-prices.ipynb**: Jupyter notebook с кодом, включая предобработку данных, обучение моделей и анализ результатов.
- **requirements.txt**: Файл со списком зависимостей, необходимых для запуска кода.

## Как использовать проект
1. Склонируйте репозиторий на свой компьютер.
2. Установите необходимые зависимости, указанные в файле `requirements.txt`.
3. Запустите Jupyter notebook `house-prices.ipynb`, следуя инструкции в нём.

## Контактная информация
Если у вас есть вопросы или предложения по улучшению проекта, свяжитесь со мной:
- Email: maximgoltsov@gmail.com

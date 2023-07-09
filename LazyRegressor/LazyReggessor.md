Для выбора оптимального алгоритма машинного обучения использовалась библиотека Lazy Predict. 
Наилучший результат на наших данных (Imputed_data.csv) при оценке с использованием инструмента lazyRegressor показала модель ExtraTreesRegressor ($R^2 = 0.80, RMSE = 3.97$), для которой с использоваинем sklearn.model_selection.GridSearchCV были подобранны оптимальные параметры (ExtraTreesRegressor(max_depth=10, min_samples_split=4, n_estimators=50, n_jobs=-1, random_state=123)) для улучшения точности предсказания ($R^2 = 0.83, RMSE = 3.68$). 
Модель ExtraTreesRegressor была обучена на полном датасете (Imputed_data.csv) и выгружена в файл ExtraTreesRegressor.sav
Также были рассчитаны признаки, вносящие наибольший вклад в предсказание:

![feature_importance](https://github.com/Riddars/Dream_team/assets/80769929/e3e49467-2bda-4809-8e53-f058f080ee98)

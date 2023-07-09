# Dream_team

# Исходные данные

Исходные данные представленны в папке raw_data

    data.csv
    bacterial_descriptors.csv
    drug_descriptors.csv

# Обработка исходных данных

Датасет data.csv был дополнен информацией о бактериях и антибиотиках, представленных в датасетах bacterial_descriptors.csv и drug_descriptors.csv соответственно.
Данные о бактериях были закодированы расстоянием на филогенетическом дереве:

![image](https://github.com/Riddars/Dream_team/assets/80769929/14b52c06-f717-4bbf-9ee8-fec0421e2ee5)

Итоговый датасет: Imputed_data.csv

# Обучение моделей машинного обучения и неронной сети

Для выбора оптимальных алгоритмов машинного обучения использовались методы AutoML PyCaret, LazyPredict LasyRegressor.
Была обучена нейронная сеть состоящая из 64 слоев.

| ------------- | ExtraTreesRegressor | Gradient Boosting Regressor | Neural Network | 
| $R^2$ | 0.83 | 0.78 | 0.84 |
| RMSE | 3.68 | 3.52 | 3.49 |


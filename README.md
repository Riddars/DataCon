![image](https://github.com/Riddars/Dream_team/assets/80769929/5bd482a3-bda3-4275-a718-5953937b817c)# Dream_team

# Исходные данные

Исходные данные представленны в папке raw_data

    data.csv
    bacterial_descriptors.csv
    drug_descriptors.csv

# Обработка исходных данных

Датасет data.csv был дополнен информацией о бактериях и антибиотиках, представленных в датасетах bacterial_descriptors.csv и drug_descriptors.csv соответственно.
Данные о бактериях были закодированы расстоянием на филогенетическом дереве:

![image](https://github.com/Riddars/Dream_team/assets/80769929/14b52c06-f717-4bbf-9ee8-fec0421e2ee5)

Итоговый датасет:
    Imputed_data.csv

![image](https://github.com/Riddars/Dream_team/assets/80769929/ddac4856-56f1-4e3a-a823-941fca9ea53b)



# Обучение моделей машинного обучения и неронной сети

Для выбора оптимальных алгоритмов машинного обучения использовались методы AutoML PyCaret, LazyPredict LasyRegressor.
Была обучена нейронная сеть состоящая из 2 слоев, включающих 64 нейрона каждый.

![image](https://github.com/Riddars/Dream_team/assets/80769929/8dbd7b7b-280e-4620-9c33-c4ea1e78279c)

Для обученных моделей машинного обучения были визуализированы важности владов признаков в предсказания МЛ.

![image](https://github.com/Riddars/Dream_team/assets/80769929/09ca342f-cee7-442f-bc01-447f1355cdf1)
![image](https://github.com/Riddars/Dream_team/assets/80769929/18088f8d-20a5-4de8-89cd-2e36b14eb462)



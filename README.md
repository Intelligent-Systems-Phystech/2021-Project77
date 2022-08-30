# 2021-Project77
## Определение фазы движения человека по сигналам носимых устройств
___
Автор: Курдюкова А.Д.
Эксперт: Стрижов В.В.
Консультанты: Кормаков Г.В., Тихонов Д.М.
___
  Решается задача восстановления фазы квазипериодических сигналов движения человека. Эти сигналы имеют повторяющиеся значения без явной периодичности. Предлагается алгоритм определения фазы движения. Он основан на представлении исходного временного ряда в фазовом пространстве. Строится траекторная матрица временного ряда. Предлагается критерий выбора оптимальной размерности траекторного пространства. Значения фазы присваиваются в соответствии с близостью точек временного ряда к аппроксимирующей модели. Результаты работы алгоритма демонстрируется на сигналах, полученных с трехосевого акселерометра. Используются пять классов периодического движения человека. Для анализа качества работы алгоритм сравнивается с методом, использующим максимумы автокорелляционной функции.
  
### Демо

[Ссылка на демо](https://github.com/Intelligent-Systems-Phystech/Kurdyukova-BS-Thesis/blob/master/code/Visualisation.ipynb)

### Requirements

[Ссылка на requirements.txt](https://github.com/Intelligent-Systems-Phystech/Kurdyukova-BS-Thesis/blob/master/code/requirements.txt)

### Код алгоритма

[Ссылка на modules.py](https://github.com/Intelligent-Systems-Phystech/Kurdyukova-BS-Thesis/blob/master/code/modules.py)

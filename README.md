# lab1

Сеть состоит из шести слоёв: 1 Flatten  и 5 Dense. В первых четырёх слоях Dense используется активация relu. В первом слое Dense используется 256 нейронов, во втором - 128, в третьем - 64, в четвёртом - 64, в пятом - 32. В обучении используются оптимизатор adam, функция потерь SparseCategoricalCrossentropy и метрика acc. Всего производится 40 эпох обучения.

Метрики точности:

![Image alt](https://github.com/dbogdan2000/lab1/blob/master/Acc.png)

![Image alt](https://github.com/dbogdan2000/lab1/blob/master/val_acc.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/lab1/blob/master/Loss.png)

![Image alt](https://github.com/dbogdan2000/lab1/blob/master/val_loss.png)

Итоговая точность на тестовых данных 0.4968


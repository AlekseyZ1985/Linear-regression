# Linear-regression
## Прочность бетона на сжатие определяет его качество и зависит от состава и особенностей технологического процесса. Обычно прочность выявляют с помощью стандартного испытания, в ходе которого специальный пресс раздавливает бетонный цилиндр определённого размера. Такие испытания требуют много времени и средств, а результаты бывают ошибочными, поэтому приходится проводить проверку заново. Альтернативный путь — выявить зависимость прочности бетона от его состава и технологии производства, используя результаты проведённых испытаний. Необходимо построить модель машинного обучения, которая реализует этот подход. Задача предсказания характеристик готового продукта в зависимости от технологических особенностей производства часто возникает в промышленности. Успешное решение подобных задач может существенно сократить издержки и ускорить производство качественного продукта.

Id - идентификатор состава.
CementComponent - количество цемента в смеси.
BlastFurnaceSlag - количество доменного шлака в смеси.
FlyAshComponent - количество зольной пыли в смеси.
WaterComponent - количество воды в смеси.
SuperplasticizerComponent - количество суперпластификатора в смеси.
CoarseAggregateComponent - количество заполнителя с грубой фракцией в смеси.
FineAggregateComponent - количество заполнителя с мелкой фракцией в смеси.
AgeInDays - время высыхания в днях.
Strength - прочность получившегося бетона (Целевая переменная)

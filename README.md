# tinkoff-advanced-dl
My solutin to Tinkoff Advanced DL enrollment task<br>


Вывод
* Аугментации по типу блюра, изменени цвета и яркости (Имитиующие плохое освещение и проблемы со съёмкой) сильно помогают моделе

Что можнно улучшить:
* Другой feature extractor, например VIT
* Подавать нескоько вреймов в СТС Loss 
* Использоать CE с весами на классы для борьбы с сильным дибалансом чаров


# Model Archetecture:
![Model Archetecture](archetecture.png)

![Training](newplot.png)

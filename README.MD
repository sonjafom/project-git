Проект: Командная строка / Git
В ходе этого проекта нужно будет создать репрозиторий проекта "Обучение с учителем", сделанного несколько спринтов назад.

Ниже приведено описание проекта "Обучение с учителем".

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Необходимо было спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Для решения поставленной задачи необходимо было определить модель с предельно большим значением F1-меры. 

Дополнительно измеряли AUC-ROC, сравнивали её значение с F1-мерой. В ходе проекта использовались такие модели, как: решающее дерево, случайный лес и логистическая регрессия.

В результате наиболее эффективной моделью оказалась модель случайного леса с количеством деревьев 100 и максимальной глубиной 10. Было выполнено сравнение этой модели с константной моделью, и случайный лес показал более высокую точность, auc-roc, recall и f1.
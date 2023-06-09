# [Выбор модели для прогнозирования оттока клиентов](https://nbviewer.jupyter.org/github/Nanobelka/bank_churn_prediction/blob/main/bank_churn_prediction.ipynb)
## На основании ряда характеристик создать портрет клиента, склонного к уходу из банка
##### Project for [Yandex.Praktikum](https://github.com/Nanobelka/Yandex_Praktikum)

**Заказчик:** некий банк.

**Входные данные:** исторические данные о характеристиках, поведении клиентов и расторжении договоров с банком.

**Цель проекта:** спрогнозировать, уйдет клиент из банка в ближайшее время или нет.

**Задачи проекта:** 

- исследовать баланс классов, обучить модель без учета дисбаланса;
- улучшить качество модели, учитывая дисбаланс классов;
- применить разные алгоритмы и выбрать лучший;
- целевая метрика и минимально приемлемое значение: **f1_score = 0.59**;
- проверить `f1_score` на тестовой выборке;
- вычислить `roc_auc_score`, сравнить с `f1_score`;
- дать рекомендации по дальнейшему развитию данного проекта.

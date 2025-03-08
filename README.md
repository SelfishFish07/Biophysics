# Отчёт по 2 заданию. Горизонты физики.

## Структура исходного белка
Aполипопротеин E4 (участвует в метаболизме липидов в организме).
![image1](/media/APOLIPOPROTEIN%20E.png)
![image1](/media/1b68_multipercentile_validation.png)

Предсказание структуры белка в AlphaFold3. pTM=0.75 > 0.5 означает, что прогнозируемый фолд может быть аналогичен истинной структуре.
![image1](/media/AF3_1.png)

## Дизайн связующего белка

Форма белкового остова, сгенерированного с помощью RFDiffusion:
![image1](/media/RFdiffusion_result.png)

https://github.com/user-attachments/assets/13d775b6-ff9f-4e6c-9bd5-c6fbca80b2dd

Сгенерированные сиквенсы:
![image1](/media/best_model.png)

Наименьшее RMSD = 3A у модели №1.
![image1](/media/Comparison.png)

Перепроверим этот сиквенс в AlphaFold3:
![image1](/media/AF3_2.png)

Показатели ipTM и pTM достаточно высокие.
Итоговый результат:

https://github.com/user-attachments/assets/254c403f-7fb2-446e-adc9-863fa81d3cc2



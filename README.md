# Отчёт по 2 заданию. Горизонты физики.

## Структура исходного белка
Исходный белок $-$ аполипопротеин E4 (участвует в метаболизме липидов в организме).
![image1](/media/APOLIPOPROTEIN%20E.png)
![image1](/media/1b68_multipercentile_validation.png)

Предсказание структуры белка в AlphaFold3. pTM=0.75 > 0.5 означает, что прогнозируемый фолд может быть аналогичен истинной структуре.
![image1](/media/AF3_1.png)

## Дизайн связующего белка

Форма белкового остова, сгенерированного с помощью RFDiffusion:
![image1](/media/RFdiffusion_result.png)
<video controls src="media/video_pred.mp4" title="Title"></video>

Сгенерированные сиквенсы:
![image1](/media/best_model.png)

Наименьшее RMSD = 3A у модели №1.
![image1](/media/Comparison.png)

Перепроверим этот сиквенс в AlphaFold3:
![image1](/media/AF3_2.png)

Показатели ipTM и pTM достаточно высокие.
Итоговый результат:

<video controls src="media/video.mp4" title="Title"></video>

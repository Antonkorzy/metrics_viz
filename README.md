# Репозиторий для иллюстрации процесса визуализации данных по метрикам

Данные взяты из БД ClickHouse и используются как логи пользовательской активности в определенном продукте. 

1. Данные были получены и обработаны в Python (AppQuantum_test_Korzukhin.ipynb).
2. После обработки были получены данные в агрегированном виде: AQ_output_arpu.csv и AQ_output_rr.csv.
3. Агрегированные данные были загружены в Tableau и по ним построены дашборды: AQ_test_Korzukhin.twb
4. Добавил небольшой анализ в файле: Анализ по результатов метрик.docx

Пример дашборда в файле: dash_example.png
![alt text](https://github.com/Antonkorzy/metrics_viz/blob/master/dash_example.PNG)

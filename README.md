### revisor_report_parser

##### Разбор отчетов АС Ревизор

Входным аргументом является отчет АС Ревизор в формтае .pdf. Пример использования

```
./check_url_rkn.sh report.pdf > report.txt
```

На выходе получаем таблицу

| Время обнаружения | Время включения записи в реестр | IP | URL/domain | 
|:-----------------:|:-------------------------------:|:--:|:----------:|
| 27 Дек, 2016 22:27:17| 29 Дек, 2015 17:13:38 | 186.5.161.20 | http://www.bookmaker.eu/ |
|     *************    |    *************    |     *************    |     *************    


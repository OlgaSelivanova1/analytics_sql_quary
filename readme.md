<H1/>TASK_1:</H1>
  Вывести все сделки и значения их атрибутов с учетом ручных корректировок.
  <p>Удалить из таблицы с автоматическими значениями записи, у которых Is_deleted_src= 1, а записям с Is_deleted_src= 0 вывести значение атрибута из таблицы manual_tbl.</p>
<H2>Данные:</H2>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/task_1.jpg" alt="tables style="width=250">
<H4>Решение:</H4>
<p><a href="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/my_quary_sql/task_1.txt">Код sql developer</a></p>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/my_result_task1.jpg" alt="result_my style="width=150">
<H1/>TASK_2:</H1>
<p>Вывести уникальные значения из столбца «a», в которых максимальное значение в столбце «b» и соответствующее значение в столбце «c».</p>
<H2>Данные:</H2>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/task_2.jpg" alt="tables style="width=200">
<H4>Решение:</H4>
<p><a href="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/my_quary_sql/task_2.sql">Код sql developer</a></p>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/my_result_task2.jpg" alt="result_my style="width=150">
<H1/>TASK_3:</H1>
  Необходимо из 2х заданных таблиц получить итоговую таблицу, в которой требуется создать новые интервалы с уникальной комбинацией полей nm_amt, client_name.
<H2>Данные:</H2>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/task_3.jpg" alt="tables">
Дополнительно:
 <p> В итоговой таблице добавить отсутствующие периоды. Считаем, что значения полей nm_amt и client_nameотсутствуют в пропущенных периодах.</p>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/task_3_result_tbl.jpg" alt="result_tables style="width=300">
<H4>Решение:</H4>
<p><a href="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/my_quary_sql/task_3.txt">Код sql developer</a></p>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/my_result_task3.jpg" alt="result_my style="width=300">
<H1/>TASK_4:</H1>
Есть исходные данные по дням формата:
<pre><p>День | Номер счета | Остаток на счете</p></pre>
В некоторые дни значений нет (нет как таковой записи в принципе).
Отсутствие значения подразумевает под собой нулевой остаток, но такие данные не хранятся.
Если значение остатка по счету изо дня в день одинаковое – в исходных данных на каждый день лежит одинаковый остаток.
<p>Нужно предложить вариант раскладки значений из дней в периоды постоянства остатка. Периоды когда остаток равен нулю тоже надо показывать.</p>
Структура итоговой таблицы:
<pre><p>Дата с  | Дата по | Номер счета | Остаток на счете</p></pre>
<H4>Решение:</H4>
<p><a href="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/my_quary_sql/task_4.txt">Код sql developer</a></p>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/my_result_task4.jpg" alt="result_my style="width=400">
<H1/>TASK_5:</H1>
Схлопнуть периоды, если у них все атрибуты одинаковые.
<H2>Данные:</H2>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/task_5.jpg" alt="result_tables style="width=400">
<H4>Решение:</H4>
<p><a href="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/my_quary_sql/task_5.txt">Код sql developer</a></p>
<img src="https://github.com/OlgaSelivanova1/analytics_sql_quary/blob/main/img.jpg/my_result_task5.jpg" alt="result_my style="width=300">





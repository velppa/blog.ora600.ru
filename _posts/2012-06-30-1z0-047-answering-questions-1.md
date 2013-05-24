---
layout: post
title: 1z0-047, разбор вопросов №1 
lang: ru
category: oracle
---

Буду кратко описывать топики, выделенные после 
[первого прохождения теста][1].

##NEXT_DAY

![NEXT_DAY](http://docs.oracle.com/cd/B19306_01/server.102/b14200/img/next_day.gif)

Возвращает дату — следующий день недели, указанный в `char` (название дня недели) после 
даты, указанной в `date`. Часы, минуты, секунды возвращаемого значения равны соответствующим 
значениям из `date`.

[Документация][NEXT_DAY_DOCS]

##Инструкция WITH CHECK OPTION у VIEW

Инструкция `WITCH CHECK OPTION` ограничивает DML операции над представлением 
строками, явно подпадающими в представление. Например, если в определении 
представления есть `WHERE job='CLERK'`, то вставить строку с `job='MANAGER'` в 
представление не получится.

[Документация][WITH_CHECK_OPTION_DOCS]

[1]: {% post_url 2012-06-18-1z0-047-test-passing-1 %}
[NEXT_DAY_DOCS]: http://docs.oracle.com/cd/B19306_01/server.102/b14200/functions093.htm
[WITH_CHECK_OPTION_DOCS]: http://docs.oracle.com/cd/B19306_01/server.102/b14200/statements_8004.htm#i2117836
# Задание 1

Чтобы удалить все пустые строки, я использовала регулярное выражение: **\n\n** . Заменила все вхождения на **\n** .

![](https://github.com/greensberg/hw9/blob/master/%D0%BF%D1%80%D0%BE%D0%B1%D0%B5%D0%BB%D1%8B.PNG)
# Задание 2

Чтобы найти всех князей и города, имя и название которых оканчивается на "слав", я использовала регулярное выражение: [А-ЯЁ][а-яёѣ]`*`слав[а-яёѣ]`*`

![](https://github.com/greensberg/hw9/blob/master/%D1%81%D0%BB%D0%B0%D0%B2%201.PNG)
 
Или регулярное выражение: [А-ЯЁ][а-яё]`*`слав[^\s.,\?!:;-]`*` 
 


Всего упоминаний о князьях и городах нашла: **592**.

# Задание 3

Чтобы найти все упоминания Новгорода, я использовала регулярное выражение: Нов(

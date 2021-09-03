# Landing-EnglishTest-Results
Заказ на верстку одной страницы:
https://newtilda1.github.io/

Предыстроия:
У заказчика была страница для выводов результата прохождения теста по английскому языку. Она была создана с помощью коструктора сайтов Tilda. 
Проблема заключалась в медленной загрузки лендинга. 
Заказчик поставил задачу сверстать адаптивный одностраничник на чистом html и css, чтобы избавиться от лишних классов, свойств и вложенности, которую добавляла Tilda.

Срок выполнения: 2 дня.
Препятствия: 
1. адаптив карточек с именем и email. 
2. при изменении размера страницы колонки с ответами должны были делиться на равное количество элементов.

Решение 1-ой проблемы было в измении метода верстки с flex на grid. 
2-я проблема решалась с помощью изменения flex-direction на column, добавления flex-wrap: wrap и изменения ширины контейнера в зависимости от ширины страницы и кол-ва необходимых столбцов.

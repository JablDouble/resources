В рамках данного задания вам необходимо создать форму для отправки информации на **почту**.

На форме будут следующие поля: ФИО, номер телефона, email, select для города и чекбокс с разрешением на хранение данных.

Для того, чтобы при нажатии кнопки произошел переход в почтовый клиент, 
вы должны поставить в `action` следующую строку: `mailto:адрес вашей электронной почты`.

В итоге получится следующее:

```html
<form action="mailto:адрес вашей электронной почты" enctype="text/plain"></form>
```
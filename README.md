# SQL
## Схема базы данных
![Схема базы данных](https://github.com/tyoshkin/SQL/blob/main/db.jpg)

Структура и описание таблиц:

**user_actions** — действия пользователей с заказами:
- user_id -	id пользователя
- order_id	-	id заказа
- action -	действие пользователя с заказом; 'create_order' — создание заказа, 'cancel_order' — отмена заказа
- time	- время совершения действия

**courier_actions** — действия курьеров с заказами:
- courier_id -	id курьера
- order_id	-	id заказа
- action	- действие курьера с заказом; 'accept_order' — принятие заказа, 'deliver_order' — доставка заказа
- time	- время совершения действия

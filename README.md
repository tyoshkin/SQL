# SQL
## [Наиболее интересные для меня задачи с курса](https://github.com/tyoshkin/SQL/blob/main/karpov.courses%20SQL)
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

**orders** — информация о заказах:
- order_id	- заказа 
- creation_time	-	время создания заказа
- product_ids	-	список id товаров в заказе
- 
**users** — информация о пользователях:
- user_id  - 	id пользователя
- birth_date -	дата рождения
- sex -	пол

**couriers** — информация о курьерах:
- courier_id 	- 	id курьера
- birth_date 	-	дата рождения
- sex -	пол

**products** — информация о товарах, которые доставляет сервис:
- product_id -	id продукта
- name 	- название товара
- price -	цена товара

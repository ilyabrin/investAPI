##Время жизни ключа идемпотентности на стороне брокера

**Ключ идемпотентности** передаваемый как параметр `order_id` в методе [postOrder](/investAPI/orders#postorder), а так же
передаваемый как `idempotency_key` в методе [replaceOrder](/investAPI/orders#replaceorder) хранится на стороне брокера и имеет срок жизни **один год**.

Счетчик стрим соединений обновляется каждые 2 минуты.
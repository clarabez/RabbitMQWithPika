# pika
Starting with [RabbitMQ](https://github.com/rabbitmq) and [Pika Python client](https://github.com/pika), following [official tutorial here](https://www.rabbitmq.com/tutorials/tutorial-one-python.html).


How to access it via localhost?
Start service, access: http://localhost:15672/

Default login and password: guest, guest.


NOTE:
Pay attention to this [issue #277](https://github.com/rabbitmq/rabbitmq-tutorials/issues/277?_pjax=%23js-repo-pjax-container) ("basic_consume() got an unexpected keyword argument 'auto_ack'") reported about parameters for `channel.basic_consume()` method.

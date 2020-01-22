A core element in any MQ protocol especially for RabbitMQ
Messages are routed to queues from exchanges
Queues are final destinations in RabbitMQ before being received by subscribers
Routing algorithms depends on the exchange type and rules called "bindings"
Bindings are simply used to bind exchanges to queues for message delivery
Properties of a Queue:
Name
Durable
Exclusive
The name of the queue
Either persist the queue to the disk or not
Delete the queue if not used anymore
Delete the queue when consumer unsubscribes
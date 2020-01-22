# Exchanges

* Actual AMQP elements where messages are sent at first
* Takes a message and routes it into one or more queues
* Routing algorithm decides where to send messages from exchange
* Routing algorithms depends on the exchange type and rules called "bindings"
* Bindings are simply used to bind exchanges to queues for message delivery


## Four Exchange Types:

Direct Exchange - amq.direct
Fanout Exchange - amq.fanout
Topic Exchange - amq.topic
Headers Exchange - amq.match and amq.headers



direct exchange is simply an empty string or amq.direct direction for any exchange.



Fan out exchanges are being used as the message distribution to everywhere for all the bindings that your exchange has.Your messages are being spread out all the queues with your bindings.


The topic exchange a key point in the topic exchange is you define a topic and you send your message using that topic. Let's suppose you're running a e-commerce site and your customer just purchased an item from your store and you want to notify some other part of your system about this customer purchase and you have a topic named as customer purchased and when you send your message with the topic exchange with this topic your message is being delivered to the Conservative Party over your messaging system.

So topic exchange is simply like the specific way of delivering messages in AMQP.

Finally we have header's exchange headboards exchange are basically the way to exchange headers with
messages in AM Cupie And of course with rabid MQ you exchange messages and you want to just maybe exchange
your headers with other messages and other queues and exchanges or maybe other consumers.
This is the way to exchange messages for headers in rabbit named Q And for the default you can use and
Cupie up match or and keep the data headers and some specific or custom header that you want to provide.


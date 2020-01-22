# Binding

* Rules that exchanges use to route messages to queues
* To instruct an exchange E to route messages to a queue Q, Q has to be bound to E!
* May have an optional routing key attribute used by some exchange types
* The routing key acts like a filter
 
## Binding Analogy:
* Queue is like your destination in Delhi (E Block, Central Secretariat, New Delhi, Delhi 110011).
* Exchange is like IGI airport in Delhi
* Bindings are routes from IGI to your destination. There can be zero or many ways to reach it

If message cannot be routed to any queue (there are no bindings for the exchanae it was published to) it is
either dropped or returned to the publisher, depending on message attributes t5e publisher has set.
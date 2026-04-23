# order-service

This is a Fastify app that provides an API for submitting orders. It is meant to be used in conjunction with the store-front app.

(https://marketplace.visualstudio.com/items?itemName=humao.rest-client) extension installed.

To view the order messages in RabbitMQ, open a browser and navigate to [http://localhost:15672](http://localhost:15672). Log in with the username and password you provided in the environment variables above. Then click on the **Queues** tab and click on your **orders** queue. After you've submitted a few orders, you should see the messages in the queue.

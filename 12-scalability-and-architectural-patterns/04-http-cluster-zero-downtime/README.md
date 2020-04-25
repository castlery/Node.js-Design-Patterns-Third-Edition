# 03-http-cluster-resilient

This example demostrates how to benchmark a simple http server that uses the cluster module and provides auto restarting of failed workers.

## Run

To run the example server:

To run the example server:

```bash
npm start # or `node app.js`
```

To run a benchmark (in another terminal):

```bash
npm run benchmark # or `npx autocannon -c 200 -d 10 http://localhost:8080`
```
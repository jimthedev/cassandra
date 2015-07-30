# cassandra with rpc / thrift

This image sets uses the latest cassandra image but sets enablethrift / start_rpc to true.

To run for production:

```bash
docker run -d --name cs1 jimthedev/cassandra
```

To build and run for development (replace name with your name):

```bash
docker build -t <NAME>/cassandra .
docker run -d --name cs1 <NAME>/cassandra
```
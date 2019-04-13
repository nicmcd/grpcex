# grpcex

A simple grpc example

## Server

Start a server with the following command:
``` sh
bazel run :grpex -- 0.0.0.0:51234
```

## Client

Run a client with the following command, requesting 10 random numbers from the server:
``` sh
bazel run :grpex -- localhost:51234 10
```

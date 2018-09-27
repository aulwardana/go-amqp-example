# go-amqp-example
Example of publisher and consumer of RabbitMQ messages over Tor Network in Golang

# Requirements

The following instructions assume that you have **Go** correctly installed (and $GOPATH set correctly), **RabbitMQ** installed with default settings, and you running **Tor Service** in your local computer.

Note: Please build the RabbitMQ hidden service using VPS first.

# Getting the library

```
go get github.com/aulwardana/amqp
```

The library is already modified by me for connect to AMQP protocol over Tor network.

# Running the code

Run the publisher:

```
cd $GOPATH/src/github.com/andreagrandi/go-amqp-example/publisher
go run publisher.go
```

Run the consumer:

```
cd $GOPATH/src/github.com/andreagrandi/go-amqp-example/consumer
go run consumer.go
```

# Credits

This source code is forked from https://github.com/andreagrandi/go-amqp-example.

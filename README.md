# ApacheMQ-5x-with-postgresql

This is a custom Docker image for ActiveMQ 5.x with PostgreSQL database.

#### Download ActiveMQ

```
./fetch-activemq.sh
```

#### Build and run the Docker image

* Build and tag the docker image
```
docker build -t stewartium/activemq .
```

*Run
```
docker run --rm -d -p 8161:8161 stewartium/activemq
```

* Visit localhost at port `8161`

```
http://localhost:8161
```


### Installation

```
git clone https://github.com/NilashishC/telegraf_kafka
cd telegraf_kafka
docker compose up -d
```

###  Read messages from the Kafka topic - EDA

```
docker exec --interactive --tty broker kafka-console-consumer --bootstrap-server broker:9092 --topic eda --from-beginning
```

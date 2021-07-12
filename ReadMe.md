follow this link to install kafka and zookeeper
https://dzone.com/articles/running-apache-kafka-on-windows-os

Helpful commands:
1. To read topic messages

kafka-console-consumer.bat --bootstrap-server localhost:9092 --<topic-name> test --from-beginning
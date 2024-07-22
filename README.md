Required Commands for windows:

.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

.\bin\windows\kafka-server-start.bat .\config\server.properties

kafka-topics.bat --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 3 --topic mohit-topic-2

kafka-topics.bat --bootstrap-server localhost:9092 --describe --topic mohit-topic-2

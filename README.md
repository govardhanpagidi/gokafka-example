# Overview

###sample GO application connecting to KAFKA and simulate messages as producer and consumer 

#Prerquistes

Run the kafka cluster either local or from confluent

place kafka(confluent) configuration in librdkafka.config file just before this repo directory 

##how to run
go run producer.go

go run consumer.go

start with ./consumer to read the messages

start with ./producer to push the messages

Note: You can produce and consume with different N number of agents by just changing the group.id of the Producer/Consumer 
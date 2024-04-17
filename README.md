# Spring Boot & Kafka Wikimedia Project
This is a sample Spring Boot project that demonstrates the integration of Kafka with a Spring Booot application.

## Requirements
- Java 17 or later
- Apache Kafka (for running locally)
- Maven

## Getting Started
### Running Kafka
Ensure that Kafka is installed and running locally. You can download Kafka from the official Apache Kafka website.

Start a ZooKeeper server (required by Kafka):

``` 
bin/zookeeper-server-start.sh config/zookeeper.properties
```

Start a Kafka broker:

``` 
bin/kafka-server-start.sh config/server.properties
```


### Project Setup
Clone this repository and navigate to the project folder:

```
    git clone https://github.com/haktanonur/KafkaSpringBootIntegration.git 
    cd KafkaSpringBootIntegration
```

### Test Project
1- Run Consumer and Producer services

2- Go to the Postman and send a request
``` 
http://localhost:8081/api/v1/wikimedia
```

![kafka_demo_application](https://github.com/haktanonur/KafkaSpringBootIntegration/assets/69698425/9d39eb8b-ea66-4d8d-81d1-2d570adab752)

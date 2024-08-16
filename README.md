# kafka-docker-files


Kafka quarkus config : 
KAFKA_SASL_MECHANISM=PLAIN
KAFKA_SECURITY_PROTOCOL=PLAINTEXT
KAFKA_STREAM_JAAS=org.apache.kafka.common.security.plain.PlainLoginModule required username="admin" password="admin-secret";
KAFKA_BOOTSTRAP_SERVERS=localhost:9092

Kafka UI:
http://localhost:8080/

RabbitMQ Config : 
username: guest
password: guest
url: localhost
port: 5672

Rabbit UI: 
http://localhost:15672/#/

#Postgres :
https://blog.cadumagalhaes.dev/how-to-setup-a-postgresql-database-with-docker-compose

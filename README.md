### create and run jar for gradle 
```bash
 ./gradlew clean build

java -jar build/libs/rabbitmq-0.0.1-SNAPSHOT.jar --spring.profiles.active=work-queues,sender

java -jar build/libs/rabbitmq-0.0.1-SNAPSHOT.jar --spring.profiles.active=work-queues,receiver
```

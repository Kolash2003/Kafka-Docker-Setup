# Kafka-Docker-Setup

- Clone this repository

- Moved inside the cloned directory and execute the following command (Make sure docker is running)

```
docker compose up -d
```

- Now once the container is up, use the following command to enter the kafka shell running inside the container

```
docker exec -it -w /opt/kafka/bin broker sh
```

# 01 Kafka

## Introduction
Apache Kafka is a data streaming platform that can handle high-throughput, fault-tolerant message streaming. It serves as the backbone for real-time data processing, event-driven architectures, and streaming analytics.

If you're following this tutorial, you probably already know what Kafka is. 

## Running Kakfka
First, run the Kafka cluster defined in our compose.yml:
```
./kafka.sh
```

This starts up a minimal Kafka environment including:
- Kafka Broker - The core message broker that stores and serves messages
- Kafka UI - A web interface for monitoring and managing topics

Open your browser to http://localhost:8080 to access Kafka UI. You'll see the cluster overview showing brokers, topics, and consumer groups.
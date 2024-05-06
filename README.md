# Realtime-Socket-Streaming-with-Apache-Spark | Realtime Data Streaming With TCP Socket, Apache Spark, OpenAI LLM, Kafka and Elasticsearch | End-to-End Data Engineering Project


## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [What You'll Learn](#what-youll-learn)
- [Technologies](#technologies)
- [Getting Started](#getting-started)


## Introduction

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline using TCP/IP Socket, Apache Spark, OpenAI LLM, Kafka and Elasticsearch. It covers each stage from data acquisition, processing, sentiment analysis with ChatGPT, production to kafka topic and connection to elasticsearch.

## System Architecture
![image](https://github.com/santhoshkrishnan30/Realtime-Socket-Streaming-with-Apache-Spark/assets/145760700/272b4bec-ca75-45d5-b79d-b05022869d26)


The project is designed with the following components:

- **Data Source**: We use `yelp.com` dataset for our pipeline.
- **TCP/IP Socket**: Used to stream data over the network in chunks
- **Apache Spark**: For data processing with its master and worker nodes.
- **Confluent Kafka**: Our cluster on the cloud
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Kafka Connect**: For connecting to elasticsearch
- **Elasticsearch**: For indexing and querying

## What You'll Learn

- Setting up data pipeline with TCP/IP 
- Real-time data streaming with Apache Kafka
- Data processing techniques with Apache Spark
- Realtime sentiment analysis with OpenAI ChatGPT
- Synchronising data from kafka to elasticsearch
- Indexing and Querying data on elasticsearch

## Technologies

- Python
- TCP/IP
- Confluent Kafka
- Apache Spark
- Docker
- Elasticsearch

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/airscholar/E2EDataEngineering.git
    ```

2. Navigate to the project directory:
    ```bash
    cd E2EDataEngineering
    ```

3. Run Docker Compose to spin up the spark cluster:
    ```bash
    docker-compose up
    ```
## How It Works

- **Socket Streaming Setup:** Establish a TCP/IP socket connection using Apache Spark to receive real-time data.

- **Sentiment Analysis:** Apply sentiment analysis using ChatGPT on the received data to extract sentiment information.

- **Integration with Kafka:** Stream the analyzed data to Kafka for distributed event processing and buffering.

- **Indexing in Elasticsearch:** Index the processed data into Elasticsearch for efficient storage and retrieval based on indexed properties.


## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change. Feel free to ask any queries or issues with this project.


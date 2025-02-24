# Building a Real Time Data Streaming Pipeline with Kafka, Spark and Elasticsearch

## Project description

A real-time data pipeline project using Kafka, MongoDB, Elasticsearch, and PySpark. Streams raw data from Kafka, enriches it with sentiment analysis using Hugging Face models, stores results in MongoDB, and visualizes data in Elasticsearch with Kibana. 

## System Architecture

![final_yelp_overview2](https://github.com/user-attachments/assets/6d0bb268-07c9-483c-be6e-ec1e6728400d)

## The architecture consists of the following components
<ul>
<li>Kafka Producer (Kaggle Notebook): Streams YELP data in real-time from a CSV file</li>
<li>Apache Spark Structured Streaming: Processes and transforms data in real-time using Spark</li>
<li>MongoDB Atlas: Serves as an intermediary storage layer for holding processed data</li>
<li>Confluent Kafka: Manages data ingestion and stream processing</li>
<li>HuggingFace Sentiment Model: DistilBERT base uncased finetuned SST-2 performs sentiment analysis on the reviews</li>
<li>Elasticsearch: Stores and indexes the data for efficient search and visualization</li>
<li>Kibana: Provides real-time visualization dashboards for exploring processed data</li>
</ul>

## Dashbord

![1](https://github.com/user-attachments/assets/9a26d6aa-f926-4604-843d-6bc087c35809)
![2](https://github.com/user-attachments/assets/a10c00bb-d9e1-4325-b867-b7611737222f)


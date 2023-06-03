# Real-Time-ClickStream-Pipeline

This project demonstrates a real-time data processing pipeline for analyzing user behavior using Scala, Apache Kafka, and Apache Spark. The pipeline ingests clickstream data, enriches it, performs sessionization, aggregation, and stores the processed data for further analysis.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Many organizations collect clickstream data from their websites or applications to gain insights into user behavior. This project showcases how Scala, Apache Kafka, and Apache Spark can be used to build a robust data processing pipeline to analyze clickstream data in real-time.

The pipeline performs various tasks including data enrichment, sessionization, aggregation, and storing the processed data. By leveraging the power of Scala, Kafka, and Spark, this project provides a foundation for understanding and implementing clickstream analysis at scale.

## Prerequisites
Before running this project, ensure that you have the following prerequisites:

- Apache Kafka: [Installation Guide](https://kafka.apache.org/documentation/)
- Apache Spark: [Installation Guide](https://spark.apache.org/downloads.html)
- Scala: [Installation Guide](https://www.scala-lang.org/download/)

## Installation
Follow these steps to set up the project:

### Clone the repository:
   ```shell
   git clone https://github.com/your-username/ClickstreamDataProcessing.git
 ```
 
### Install project dependencies: 
   ```shell
      cd ClickstreamDataProcessing
      # Run the command to install dependencies (e.g., using sbt or Maven)
   ```
## Usage 
1. Start Apache Kafka and create a topic to store clickstream data
2. Configure Apache Spark to collect with Kafka for Data ingestion.
3. Ingest Clickstream Data:
      * Run the kafka producer program in scala to simulate or collect clickstream data. Configure the producer tos send data to kafka topic creaed in step 1.

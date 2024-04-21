# StreamIt | Realtime Data Streaming | End-to-End Data Engineering Project
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-007A88?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Zookeeper](https://img.shields.io/badge/Apache%20Zookeeper-2196F3?style=for-the-badge&logo=apachezookeeper&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)




## Overview

Introducing "StreamIt": a cutting-edge real-time data engineering project designed to revolutionize data processing and analysis. By seamlessly integrating diverse technologies such as Apache Airflow, Kafka, Spark, Hadoop, and Cassandra, StreamIt offers an end-to-end solution for ingesting, streaming, processing, and storing data. From fetching user data from APIs to performing complex transformations and storing insights in a fault-tolerant database, StreamIt empowers organizations to harness the power of real-time data for informed decision-making and strategic insights.


## System Architecture


<img src="./StreamIt.png" width="100%" /> <br>

The project is designed with the following components:

- **Data Source**: We use `randomuser.me` API to generate random user data for our pipeline.
- **Apache Airflow**: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Used for streaming data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Apache Spark**: For data processing with its master and worker nodes.
- **Cassandra**: Where the processed data will be stored.



## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/airscholar/e2e-data-engineering.git
    ```

2. Navigate to the project directory:
    ```bash
    cd e2e-data-engineering
    ```

3. Run Docker Compose to spin up the services:
    ```bash
    docker-compose up
    ```

For more detailed instructions, please check out the video tutorial linked below.


## Demo

[![DEMO](https://img.youtube.com/vi/QVMjmhSHeOk/0.jpg)](https://www.youtube.com/watch?v=QVMjmhSHeOk)

## Contributors <a id="contributors"></a>

-  [Hayden Cordeiro](https://hayden.co.in/)<br>
   [![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haydencordeiro/)
   [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/haydencordeiro)


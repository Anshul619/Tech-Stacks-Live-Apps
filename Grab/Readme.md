# Grab Tech Stack

| Purpose                                             | Service                                                                                                                           |
|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Cloud Platform                                      | [AWS](https://github.com/Anshul619/AWS-Services/tree/main/Readme.md)                                                              |
| OLTP - Transaction-DB (like orders etc.)            | [DynamoDB](https://github.com/Anshul619/AWS-Services/tree/main/1_Databases/AmazonDynamoDB/Readme.md)                              |
| OLAP - Analytical-Queries (like order history etc.) | [MySQL - Amazon RDS](https://github.com/Anshul619/HLD-System-Designs/tree/main/3_Databases/7_SQL-Databases/Readme.md)             |
| Data Streaming                                      | [Kafka](https://github.com/Anshul619/HLD-System-Designs/tree/main/4_MessageBrokersEDA/Kafka/Readme.md)                            |
| Search-DB (derived data)                            | [ElasticSearch](https://github.com/Anshul619/HLD-System-Designs/tree/main/3_Databases/9_Search-Databases/ElasticSearch/Readme.md) |
| Backend Language                                    | [GoLang](GoLangBackend.md)                                                                                                        |
| Container Orchestration                             | [Kubernates](https://github.com/Anshul619/HLD-System-Designs/tree/main/9_Container&Orchestration/Kubernates/Readme.md)            |
| Object Store, Data Lake                             | [Amazon S3](https://github.com/Anshul619/AWS-Services/tree/main/6_FileStorages/3_S3ObjectStorage/Readme.md)                       |
| Graph Database                                      | [Amazon Neptune](https://github.com/Anshul619/AWS-Services/tree/main/1_Databases/AmazonNeptune.md)                                |
| InMemory Cache                                      | [Redis](https://github.com/Anshul619/HLD-System-Designs/tree/main/3_Databases/8_Caching-InMemory-Databases/Redis/Readme.md)       |
| Logging                                             | [ELK](https://engineering.grab.com/structured-logging)                                                                            |

# Use Cases

| Use Case                                          |
|---------------------------------------------------|
| [Order Processing](OrderProcessing/Readme.md)     |
| [Search Indexes Optimization](SearchIndexing.md)  |
| [Graph Service Platform](GraphServicePlatform.md) |
| [Kafka as Message Broker](KafkaMessageBroker.md)  |

# Read more
- [Real-time data ingestion in Grab](https://engineering.grab.com/real-time-data-ingestion)
- [Trident - Real-time Event Processing at Scale](https://engineering.grab.com/trident-real-time-event-processing-at-scale)
- [Plumbing At Scale](https://engineering.grab.com/plumbing-at-scale)
- [A Lean and Scalable Data Pipeline to Capture Large Scale Events and Support Experimentation Platform](https://engineering.grab.com/experimentation-platform-data-pipeline)
- [How We Designed the Quotas Microservice to Prevent Resource Abuse?](https://engineering.grab.com/quotas-service)

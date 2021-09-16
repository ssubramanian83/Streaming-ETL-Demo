# Streaming-ETL-Demo - Enriching event stream data with CDC data from Postgres, stream into Elasticsearch
Streaming ETL Demo artifacts
<div align="center" padding=25px>
    <img src="Images/confluent.png" width=50% height=50%>
</div>

# <div align="center">Streaming ETL with Confluent</div>
## <div align="center">Lab Guide</div>

## **Pre-reqs**
* `git`
* `jq`
* Docker

## **Steps**
1. [Log Into Confluent Cloud](#step-1)
2. [Create an Environment and Cluster](#step-2)
3. [Create a Schema Registry Instance](#step-3)
4. [Setup ksqlDB](#step-4)
5. [Create a Topic using the Cloud UI](#step-5)
6. [Create an API Key Pair](#step-6)
7. [Start Debezium connector, Postgres instance and Elasticsearch cluster](#step-7)
8. [Create debezium connector for Postgres](#step-8)
## Load
9. [Insert data into Postgres tables](#step-9)
10. [Check messages in Conlfuent Cloud](#step-10)
## Transform
11. [Enrich and Transform the data using ksqlDB](#step-11)
## Load
12. [Load the data into ElasticSearch](#step-12)
13. [Clean Up Resources](#step-13)
14. [Confluent Resources and Further Testing](#confluent-resources-and-further-testing)

***

## **Architecture Diagram**

<div align="center">
    <img src="" width=75% height=75%>
</div>

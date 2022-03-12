 [Learn Elasticsearch from scratch and begin learning the ELK stack (Elasticsearch, Logstash & Kibana) and Elastic Stack.](https://www.udemy.com/course/elasticsearch-complete-guide/learn/lecture/7373340#overview)

- [What is ElasticSearch?](#what-is-elasticsearch)
  - [Build a powerful search engine.](#build-a-powerful-search-engine)
  - [Query & analyze structured data](#query--analyze-structured-data)
    - [Examples:](#examples)
      - [Analyze application logs and system metrics](#analyze-application-logs-and-system-metrics)
      - [Send events to Elasticsearch](#send-events-to-elasticsearch)
      - [Excellent at analyzing lots of data](#excellent-at-analyzing-lots-of-data)
      - [Forecast future values with machine learning](#forecast-future-values-with-machine-learning)
- [How does ElasticSearch work?](#how-does-elasticsearch-work)
  - [Data is tore as documents.](#data-is-tore-as-documents)
  - [A document's data is separated into fields](#a-documents-data-is-separated-into-fields)
  - [Querying Elasticsearch](#querying-elasticsearch)
  - [Written in Java, build on Apache Lucene](#written-in-java-build-on-apache-lucene)
  - [Easy to use, and highly scalable](#easy-to-use-and-highly-scalable)
  - [🔥 Hottest name in search Engines](#-hottest-name-in-search-engines)

# What is ElasticSearch?
LeasticSearch is a search engine that is used to store and retrieve data. It is a distributed, scalable, and highly available search engine. 

## Build a powerful search engine.
- Enable search for different types of data
  - like google
  - This includes auto-completion, correcting typos, highlighting matches, handling synonyms, adjusting relevance, etc.
  ![search like google](pictures/introduction%20to%20elasticsearch/search-like-google.png)
  - Can take other factors into account, like location, time, etc.
- search like amazon
  ![search like amazon](pictures/introduction%20to%20elasticsearch/search-like-amazon.png)

## Query & analyze structured data

![query and analyze structured data](pictures/introduction%20to%20elasticsearch/query-and-analyze-structured-data.png)

You can write queries that aggregate data and use the results for making pie charts, line charts, or whatever you might need. Elasticsearch is not really a business intelligence solution, but you can indeed get a lot of valuable information out of the data that you store within Elasticsearch.

### Examples:

#### Analyze application logs and system metrics
E.g. errors and CPU/memonry usage, etc.

Or also knows as Application Performance Management (APM).

#### Send events to Elasticsearch
E.g. sales, website clicks, phone calls, etc.

#### Excellent at analyzing lots of data

#### Forecast future values with machine learning

![predicting-future-number-of-calls](pictures/introduction%20to%20elasticsearch/predicting-future-number-of-calls.png)

![anomality-detection](pictures/introduction%20to%20elasticsearch/anomality-detection.png)

This course main focus is search functionality.

# How does ElasticSearch work?

## Data is tore as documents.
Similar to rows in relational databases (e.g. MySQL, PostgreSQL, etc.).

## A document's data is separated into fields
Similar to columns in relational databases.

![example-document](pictures/introduction%20to%20elasticsearch/example-document.png)

## Querying Elasticsearch

Similar to quering a Rest API.
![querying-elasticsearch](pictures/introduction%20to%20elasticsearch/querying-elasticsearch.png)

Also written in Jason.

## Written in Java, build on Apache Lucene

## Easy to use, and highly scalable

Since Elasticsearch is distributed by nature, it scales very well in terms of increasing data volumes and query throughput. So even if you need to search through millions of documents, searches are still going to be lightning fast!

## 🔥 Hottest name in search Engines
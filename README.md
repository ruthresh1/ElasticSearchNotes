# ElasticSearchNotes
Notes on the ELK stack

Elastic search is a service part of the ELK stack (ElasticSearch, Logstash, Kibana)
Elastic search is a serarch engine, primarily used for searching contents from a data store, aggregating logs, for analytics and processing data for insights. So if you are in a product website and searching for a particular product or its feature, elastic search powers this search to give you expected relevant results, along with auto-completing the search key quickly. It lets you index, search and manage your data.

Table of differences between ElasticSearch, SQL and Mongodb

| Elasticsearch | SQL | MongoDB |
| ----------- | ----------- | -------- |
| Index (indices) | Database | Database | 
| Mapping/Type | Table | Collection | 
| Field | Column | Field |
| Object (JSON object) | Record (tuples) | Record (BSON object) |

## Elastic Search communication methods
* REST calls
* Native method

## Download Elastic Search from
https://www.elastic.co/downloads/elasticsearch
Download the latest or required version, unzip and run
```bash
% tar zxf elasticsearch-*.tar.gz
% cd elasticsearch-*
% bin/elasticsearch
```

## File structure and contents of installed Elastic search
* bin
  * files to start and manage elastic search service
  * elasticsearch, plugin
* config
  * related to configuration and setup
  * elasticsearch.yml, log4j2.properties
* lib
  * libraries needed to run elasticsearch
* modules
* plugins

## Types of nodes in a cluster
* master
* injest
* client (load balancer)
* data node

## Different use-cases 
* as primary backend for the site
* adding it to an existing system
* as ready-made solution built around it

## Features
* indexing and searching data (obviously)
* search through rest API, query using filters
* caching 
* real-time analytics using aggregations
* organizing data
* clustered elastic servers

## Books on ElasticSearch
* ElasticSearch in action
* Advanced Elasticsearch 7.0
* Learning Elasticsearch
* Elasticsearch: Definitive Guide
* Mastering Elasticsearch

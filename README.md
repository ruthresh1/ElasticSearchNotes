# ElasticSearchNotes
Notes on the ELK stack

Elastic search is a service part of the ELK stack (ElasticSearch, Logstash, Kibana)

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


## Books on ElasticSearch
* Advanced Elasticsearch 7.0
* Learning Elasticsearch
* Elasticsearch: Definitive Guide
* Mastering Elasticsearch

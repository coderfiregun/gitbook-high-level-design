---
description: Tech Essentials to know beforehand
---

# Tech Tools - Prerequisite

## HLD Interview Tech Stack Guide

Exhaustive list of technologies with curated resources for High-Level Design interviews.

**Total Technologies: 60+ | Total Resources: 180+**

***

### Table of Contents

* Databases - SQL
* Databases - NoSQL
* Caching
* Message Queue & Streaming
* Stream Processing
* Batch Processing
* Search & Analytics
* Coordination & Configuration
* Gateway & Load Balancing
* Container Orchestration
* Monitoring & Observability
* Graph Databases
* Time-Series Databases
* Object Storage
* CDN
* Service Mesh
* Workflow Orchestration
* API Protocols
* System Design Fundamentals

***

### Databases - SQL

#### PostgreSQL

1. [PostgreSQL Architecture Overview](https://www.postgresql.org/docs/current/tutorial-arch.html)
2. [Indexing Strategies](https://www.postgresql.org/docs/current/indexes.html)
3. [MVCC and Transactions](https://www.postgresql.org/docs/current/mvcc.html)

#### MySQL

1. [MySQL Architecture](https://dev.mysql.com/doc/refman/8.0/en/pluggable-storage-overview.html)
2. [InnoDB Storage Engine](https://dev.mysql.com/doc/refman/8.0/en/innodb-storage-engine.html)
3. [Replication](https://dev.mysql.com/doc/refman/8.0/en/replication.html)

***

### Databases - NoSQL

#### MongoDB

1. [MongoDB Architecture Guide](https://www.mongodb.com/docs/manual/core/databases-and-collections/)
2. [Sharding](https://www.mongodb.com/docs/manual/sharding/)
3. [Replication](https://www.mongodb.com/docs/manual/replication/)

#### Cassandra

1. [Cassandra Architecture](https://cassandra.apache.org/doc/latest/cassandra/architecture/overview.html)
2. [Data Distribution](https://cassandra.apache.org/doc/latest/cassandra/architecture/dynamo.html)
3. [Understanding Consistency](https://cassandra.apache.org/doc/latest/cassandra/architecture/guarantees.html)

#### DynamoDB

1. [DynamoDB Core Components](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html)
2. [Partitions and Data Distribution](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.Partitions.html)
3. [Read Consistency](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadConsistency.html)

***

### Caching

#### Redis

1. [Redis Data Types](https://redis.io/docs/data-types/)
2. [Persistence Options](https://redis.io/docs/management/persistence/)
3. [Replication](https://redis.io/docs/management/replication/)
4. [Redis Cluster](https://redis.io/docs/management/scaling/)

#### Memcached

1. [Memcached Architecture](https://github.com/memcached/memcached/wiki/Overview)
2. [Memcached vs Redis](https://aws.amazon.com/elasticache/redis-vs-memcached/)

***

### Message Queue & Streaming

#### Apache Kafka

1. [Kafka Introduction](https://kafka.apache.org/documentation/#introduction)
2. [Kafka Architecture](https://kafka.apache.org/documentation/#design)
3. [Producer & Consumer](https://kafka.apache.org/documentation/#producerapi)
4. [Replication Protocol](https://kafka.apache.org/documentation/#replication)
5. [Confluent: Kafka in a Nutshell](https://www.confluent.io/blog/apache-kafka-intro-how-kafka-works/)

#### RabbitMQ

1. [RabbitMQ Concepts](https://www.rabbitmq.com/tutorials/tutorial-one-python.html)
2. [Reliability Guide](https://www.rabbitmq.com/reliability.html)
3. [Clustering](https://www.rabbitmq.com/clustering.html)

#### AWS SQS/SNS

1. [SQS Core Concepts](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
2. [SNS Overview](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)
3. [SQS vs SNS vs Kinesis](https://aws.amazon.com/sqs/faqs/)

#### Apache Pulsar

1. [Pulsar Concepts](https://pulsar.apache.org/docs/concepts-overview/)
2. [Architecture Overview](https://pulsar.apache.org/docs/concepts-architecture-overview/)

***

### Stream Processing

#### Apache Flink

1. [Flink Architecture](https://nightlies.apache.org/flink/flink-docs-master/docs/concepts/flink-architecture/)
2. [Stateful Stream Processing](https://nightlies.apache.org/flink/flink-docs-master/docs/concepts/stateful-stream-processing/)
3. [Event Time & Watermarks](https://nightlies.apache.org/flink/flink-docs-master/docs/concepts/time/)
4. [Ververica: Flink Intro](https://www.ververica.com/what-is-apache-flink)

#### Apache Spark Streaming

1. [Spark Architecture](https://spark.apache.org/docs/latest/cluster-overview.html)
2. [Structured Streaming](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)
3. [RDD Programming Guide](https://spark.apache.org/docs/latest/rdd-programming-guide.html)

#### Apache Storm

1. [Storm Concepts](https://storm.apache.org/releases/current/Concepts.html)
2. [Guaranteeing Message Processing](https://storm.apache.org/releases/current/Guaranteeing-message-processing.html)

***

### Batch Processing

#### Apache Spark

1. [Spark Overview](https://spark.apache.org/docs/latest/index.html)
2. [RDD vs DataFrame vs Dataset](https://spark.apache.org/docs/latest/sql-programming-guide.html)
3. [Performance Tuning](https://spark.apache.org/docs/latest/tuning.html)

#### Apache Hadoop/MapReduce

1. [Hadoop Architecture](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html)
2. [MapReduce Tutorial](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html)

***

### Search & Analytics

#### Elasticsearch

1. [Elasticsearch Intro](https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html)
2. [Index and Search](https://www.elastic.co/guide/en/elasticsearch/reference/current/search-your-data.html)
3. [Scaling Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/scalability.html)
4. [Shards and Replicas](https://www.elastic.co/guide/en/elasticsearch/reference/current/index-modules.html)

#### Kibana

1. [Kibana Overview](https://www.elastic.co/guide/en/kibana/current/introduction.html)
2. [Visualizations](https://www.elastic.co/guide/en/kibana/current/dashboard.html)

#### Apache Solr

1. [Solr Tutorial](https://solr.apache.org/guide/solr/latest/getting-started/solr-tutorial.html)
2. [SolrCloud Architecture](https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-types.html)

***

### Coordination & Configuration

#### Apache ZooKeeper

1. [ZooKeeper Overview](https://zookeeper.apache.org/doc/current/zookeeperOver.html)
2. [ZooKeeper Programmer's Guide](https://zookeeper.apache.org/doc/current/zookeeperProgrammers.html)

#### etcd

1. [etcd Documentation](https://etcd.io/docs/latest/)
2. [etcd Architecture](https://etcd.io/docs/latest/learning/why/)

#### Consul

1. [Consul Introduction](https://developer.hashicorp.com/consul/docs/intro)
2. [Service Discovery](https://developer.hashicorp.com/consul/docs/concepts/service-discovery)

***

### Gateway & Load Balancing

#### Nginx

1. [Nginx Architecture](https://nginx.org/en/docs/beginners_guide.html)
2. [Load Balancing](https://docs.nginx.com/nginx/admin-guide/load-balancer/http-load-balancer/)
3. [Reverse Proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)

#### HAProxy

1. [HAProxy Intro](https://www.haproxy.org/download/2.8/doc/intro.txt)
2. [Configuration Manual](https://www.haproxy.org/download/2.8/doc/configuration.txt)

#### Kong

1. [Kong Gateway](https://docs.konghq.com/gateway/latest/)
2. [Kong Architecture](https://docs.konghq.com/gateway/latest/get-started/comprehensive/)

***

### Container Orchestration

#### Kubernetes

1. [K8s Architecture](https://kubernetes.io/docs/concepts/architecture/)
2. [Workloads](https://kubernetes.io/docs/concepts/workloads/)
3. [Services & Networking](https://kubernetes.io/docs/concepts/services-networking/)
4. [Storage](https://kubernetes.io/docs/concepts/storage/)

#### Docker

1. [Docker Overview](https://docs.docker.com/get-started/overview/)
2. [Container Networking](https://docs.docker.com/network/)

***

### Monitoring & Observability

#### Prometheus

1. [Prometheus Overview](https://prometheus.io/docs/introduction/overview/)
2. [Data Model](https://prometheus.io/docs/concepts/data_model/)
3. [Querying Basics](https://prometheus.io/docs/prometheus/latest/querying/basics/)

#### Grafana

1. [Grafana Fundamentals](https://grafana.com/docs/grafana/latest/fundamentals/)
2. [Dashboards](https://grafana.com/docs/grafana/latest/dashboards/)

#### Jaeger

1. [Jaeger Architecture](https://www.jaegertracing.io/docs/latest/architecture/)
2. [Getting Started](https://www.jaegertracing.io/docs/latest/getting-started/)

#### ELK Stack

1. [ELK Stack Overview](https://www.elastic.co/elastic-stack)
2. [Logstash](https://www.elastic.co/guide/en/logstash/current/introduction.html)

***

### Graph Databases

#### Neo4j

1. [Graph Database Concepts](https://neo4j.com/docs/getting-started/appendix/graphdb-concepts/)
2. [Cypher Query Language](https://neo4j.com/docs/cypher-manual/current/introduction/)

***

### Time-Series Databases

#### InfluxDB

1. [InfluxDB Key Concepts](https://docs.influxdata.com/influxdb/v2/reference/key-concepts/)
2. [Data Model](https://docs.influxdata.com/influxdb/v2/reference/key-concepts/data-elements/)

#### TimescaleDB

1. [TimescaleDB Architecture](https://docs.timescale.com/about/latest/architecture/)
2. [Hypertables](https://docs.timescale.com/about/latest/architecture/hypertables-and-chunks/)

***

### Object Storage

#### AWS S3

1. [S3 Storage Classes](https://aws.amazon.com/s3/storage-classes/)
2. [S3 Performance](https://docs.aws.amazon.com/AmazonS3/latest/userguide/optimizing-performance.html)
3. [S3 Consistency Model](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html#ConsistencyModel)

#### MinIO

1. [MinIO Architecture](https://min.io/docs/minio/linux/operations/concepts.html)
2. [Erasure Coding](https://min.io/docs/minio/linux/operations/concepts/erasure-coding.html)

***

### CDN

#### CloudFront / CDN Basics

1. [CloudFront Overview](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
2. [How CDNs Work](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)

***

### Service Mesh

#### Istio

1. [Istio Architecture](https://istio.io/latest/docs/ops/deployment/architecture/)
2. [Traffic Management](https://istio.io/latest/docs/concepts/traffic-management/)

#### Linkerd

1. [Linkerd Architecture](https://linkerd.io/2.14/reference/architecture/)

***

### Workflow Orchestration

#### Apache Airflow

1. [Airflow Concepts](https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/index.html)
2. [Architecture Overview](https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/overview.html)

#### Temporal

1. [Temporal Overview](https://docs.temporal.io/temporal)
2. [Key Concepts](https://docs.temporal.io/workflows)

***

### API Protocols

#### REST

1. [REST API Tutorial](https://restfulapi.net/)
2. [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)

#### GraphQL

1. [GraphQL Introduction](https://graphql.org/learn/)
2. [Best Practices](https://graphql.org/learn/best-practices/)

#### gRPC

1. [gRPC Introduction](https://grpc.io/docs/what-is-grpc/introduction/)
2. [Core Concepts](https://grpc.io/docs/what-is-grpc/core-concepts/)

***

### System Design Fundamentals

#### CAP Theorem

1. [CAP Theorem Explained](https://www.ibm.com/topics/cap-theorem)
2. [CAP FAQ](https://www.the-paper-trail.org/page/cap-faq/)

#### Consistent Hashing

1. [Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing)
2. [Tom White on Consistent Hashing](https://tom-e-white.com/2007/11/consistent-hashing.html)

#### Rate Limiting

1. [Rate Limiting Strategies](https://cloud.google.com/architecture/rate-limiting-strategies-techniques)
2. [Kong Rate Limiting](https://konghq.com/blog/engineering/how-to-design-a-scalable-rate-limiting-algorithm)

#### Distributed Consensus

1. [Raft Consensus](https://raft.github.io/)
2. [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)

***

### Pro Tips for HLD Interviews

* **Focus on trade-offs** rather than memorizing features
* Always ask about **scale, consistency requirements, and failure scenarios**
* Practice explaining **why** you'd choose one technology over another
* **Hands-on experience** (even toy projects) > theoretical knowledge
* Read official docs first, then deep-dive into architecture blogs from Netflix, Uber, LinkedIn
* Understand the **CAP theorem** implications for each technology
* Know the difference between **consistency models** (strong, eventual, causal)
* Be ready to discuss **scalability patterns** (sharding, partitioning, replication)
* Understand **failure modes** and recovery mechanisms for each tech

***

**Last Updated:** November 2025

# Why and What Tech

## Exhaustive HLD Technologies - Deep Technical Understanding

### **🔴 Caching & In-Memory Stores**

| **Technology**                 | **Best Learning Resource**                                                                                     | **Official Docs**                      |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| **Redis**                      | https://redis.io/docs/manual/patterns/                                                                         | https://redis.io/docs/                 |
| **Redis - Twitter Use Case**   | https://blog.twitter.com/engineering/en\_us/topics/infrastructure/2014/caching-with-twemcache                  | -                                      |
| **Redis - Instagram Use Case** | https://instagram-engineering.com/storing-hundreds-of-millions-of-simple-key-value-pairs-in-redis-1091ae80f74c | -                                      |
| **Memcached**                  | https://github.com/memcached/memcached/wiki/TutorialCachingStory                                               | https://memcached.org/                 |
| **Facebook Memcached**         | https://research.facebook.com/publications/scaling-memcache-at-facebook/                                       | -                                      |
| **Hazelcast**                  | https://hazelcast.com/resources/distributed-caching/                                                           | https://docs.hazelcast.com/            |
| **Apache Ignite**              | https://ignite.apache.org/use-cases.html                                                                       | https://ignite.apache.org/docs/latest/ |
| **Aerospike**                  | https://aerospike.com/blog/aerospike-architecture/                                                             | https://docs.aerospike.com/            |

### **📨 Message Queues & Streaming**

| **Technology**               | **Best Learning Resource**                                                                 | **Official Docs**                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| **Kafka**                    | https://engineering.linkedin.com/kafka/running-kafka-scale                                 | https://kafka.apache.org/documentation/                      |
| **Kafka - Uber Use Case**    | https://eng.uber.com/kafka/                                                                | -                                                            |
| **Kafka - Netflix Use Case** | https://netflixtechblog.com/kafka-inside-keystone-pipeline-dd5aeabaf6bb                    | -                                                            |
| **Kafka Internals**          | https://developer.confluent.io/learn-kafka/architecture/get-started/                       | -                                                            |
| **RabbitMQ**                 | https://www.rabbitmq.com/tutorials/tutorial-one-python.html                                | https://www.rabbitmq.com/documentation.html                  |
| **RabbitMQ vs Kafka**        | https://www.confluent.io/blog/kafka-fastest-messaging-system/                              | -                                                            |
| **Apache Pulsar**            | https://pulsar.apache.org/case-studies/                                                    | https://pulsar.apache.org/docs/                              |
| **Amazon SQS**               | https://aws.amazon.com/sqs/features/                                                       | https://docs.aws.amazon.com/sqs/                             |
| **Amazon Kinesis**           | https://aws.amazon.com/blogs/big-data/streaming-data-solutions-on-aws-with-amazon-kinesis/ | https://docs.aws.amazon.com/kinesis/                         |
| **NATS**                     | https://nats.io/blog/tech-advisories/                                                      | https://docs.nats.io/                                        |
| **ActiveMQ**                 | https://activemq.apache.org/components/artemis/documentation/                              | https://activemq.apache.org/components/classic/documentation |

### **⚡ Stream Processing**

| **Technology**               | **Best Learning Resource**                                       | **Official Docs**                                                     |
| ---------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------- |
| **Apache Flink**             | https://flink.apache.org/what-is-flink/use-cases/                | https://nightlies.apache.org/flink/flink-docs-stable/                 |
| **Flink - Uber Use Case**    | https://eng.uber.com/real-time-exactly-once-ad-event-processing/ | -                                                                     |
| **Flink - Alibaba Use Case** | https://flink.apache.org/2019/02/28/scaling-flink-alibaba.html   | -                                                                     |
| **Apache Storm**             | https://storm.apache.org/releases/current/Tutorial.html          | https://storm.apache.org/releases/current/index.html                  |
| **Apache Samza**             | https://samza.apache.org/learn/documentation/latest/             | https://samza.apache.org/                                             |
| **Spark Streaming**          | https://spark.apache.org/streaming/                              | https://spark.apache.org/docs/latest/streaming-programming-guide.html |
| **Kafka Streams**            | https://kafka.apache.org/documentation/streams/                  | https://docs.confluent.io/platform/current/streams/index.html         |
| **AWS Kinesis Analytics**    | https://aws.amazon.com/kinesis/data-analytics/                   | https://docs.aws.amazon.com/kinesisanalytics/                         |

### **💾 NoSQL Databases**

#### **Wide-Column Stores**

| **Technology**                     | **Best Learning Resource**                                                                                          | **Official Docs**                        |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| **Cassandra**                      | https://www.datastax.com/blog/cassandra-understanding-the-basics                                                    | https://cassandra.apache.org/doc/latest/ |
| **Cassandra - Netflix Use Case**   | https://netflixtechblog.com/benchmarking-cassandra-scalability-on-aws-over-a-million-writes-per-second-39f45f066c9e | -                                        |
| **Cassandra - Discord Use Case**   | https://discord.com/blog/how-discord-stores-billions-of-messages                                                    | -                                        |
| **Cassandra - Instagram Use Case** | https://instagram-engineering.com/open-sourcing-a-10x-reduction-in-apache-cassandra-tail-latency-d64f86b43589       | -                                        |
| **HBase**                          | https://hbase.apache.org/book.html#arch.overview                                                                    | https://hbase.apache.org/                |
| **ScyllaDB**                       | https://www.scylladb.com/product/technology/                                                                        | https://docs.scylladb.com/               |
| **Bigtable (Google Cloud)**        | https://cloud.google.com/bigtable/docs/overview                                                                     | https://cloud.google.com/bigtable/docs   |

#### **Document Stores**

| **Technology**                 | **Best Learning Resource**                                                                           | **Official Docs**                         |
| ------------------------------ | ---------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| **MongoDB**                    | https://www.mongodb.com/basics                                                                       | https://www.mongodb.com/docs/             |
| **MongoDB - Uber Use Case**    | https://www.mongodb.com/blog/post/ubernomics-a-deep-dive-into-ubers-engineering-and-business-journey | -                                         |
| **CouchDB**                    | https://docs.couchdb.org/en/stable/intro/overview.html                                               | https://docs.couchdb.org/                 |
| **DynamoDB**                   | https://aws.amazon.com/dynamodb/getting-started/                                                     | https://docs.aws.amazon.com/dynamodb/     |
| **DynamoDB - Amazon Use Case** | https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf                                | -                                         |
| **Couchbase**                  | https://docs.couchbase.com/home/index.html                                                           | https://www.couchbase.com/products/server |

#### **Key-Value Stores**

| **Technology** | **Best Learning Resource**                                          | **Official Docs**          |
| -------------- | ------------------------------------------------------------------- | -------------------------- |
| **Redis**      | \[See above in Caching]                                             | -                          |
| **Riak**       | https://riak.com/posts/technical/vector-clocks-revisited/index.html | https://docs.riak.com/     |
| **etcd**       | https://etcd.io/docs/v3.5/learning/                                 | https://etcd.io/docs/      |
| **Consul**     | https://www.consul.io/docs/architecture                             | https://www.consul.io/docs |

#### **Graph Databases**

| **Technology**              | **Best Learning Resource**                               | **Official Docs**                    |
| --------------------------- | -------------------------------------------------------- | ------------------------------------ |
| **Neo4j**                   | https://neo4j.com/developer/graph-database/              | https://neo4j.com/docs/              |
| **Neo4j - Airbnb Use Case** | https://neo4j.com/blog/building-airbnbs-knowledge-graph/ | -                                    |
| **Amazon Neptune**          | https://aws.amazon.com/neptune/                          | https://docs.aws.amazon.com/neptune/ |
| **JanusGraph**              | https://docs.janusgraph.org/                             | https://janusgraph.org/              |
| **ArangoDB**                | https://www.arangodb.com/docs/stable/                    | https://www.arangodb.com/            |
| **DGraph**                  | https://dgraph.io/docs/                                  | https://dgraph.io/                   |

### **🗄️ SQL Databases & NewSQL**

| **Technology**                    | **Best Learning Resource**                                               | **Official Docs**                                             |
| --------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------- |
| **PostgreSQL**                    | https://www.postgresql.org/docs/current/tutorial.html                    | https://www.postgresql.org/docs/                              |
| **Postgres - Instagram Use Case** | https://instagram-engineering.com/sharding-ids-at-instagram-1cf5a71e5a5c | -                                                             |
| **MySQL**                         | https://dev.mysql.com/doc/refman/8.0/en/                                 | https://dev.mysql.com/doc/                                    |
| **MySQL - Uber Migration**        | https://eng.uber.com/postgres-to-mysql-migration/                        | -                                                             |
| **Vitess (MySQL Sharding)**       | https://vitess.io/docs/overview/                                         | https://vitess.io/docs/                                       |
| **CockroachDB**                   | https://www.cockroachlabs.com/docs/stable/architecture/overview.html     | https://www.cockroachlabs.com/docs/                           |
| **TiDB**                          | https://docs.pingcap.com/tidb/stable                                     | https://www.pingcap.com/                                      |
| **YugabyteDB**                    | https://docs.yugabyte.com/preview/architecture/                          | https://docs.yugabyte.com/                                    |
| **Google Spanner**                | https://cloud.google.com/spanner/docs/whitepapers                        | https://cloud.google.com/spanner/docs                         |
| **Aurora (AWS)**                  | https://aws.amazon.com/rds/aurora/                                       | https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/ |

### **🔍 Search Engines**

| **Technology**                        | **Best Learning Resource**                                                               | **Official Docs**                       |
| ------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------- |
| **Elasticsearch**                     | https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html | https://www.elastic.co/guide/index.html |
| **Elasticsearch - Uber Use Case**     | https://eng.uber.com/elasticsearch-query-rewriting/                                      | -                                       |
| **Elasticsearch - LinkedIn Use Case** | https://engineering.linkedin.com/blog/2021/upgrading-elasticsearch-at-linkedin           | -                                       |
| **Solr**                              | https://solr.apache.org/guide/solr/latest/getting-started/introduction.html              | https://solr.apache.org/guide/          |
| **Algolia**                           | https://www.algolia.com/doc/                                                             | https://www.algolia.com/developers/     |
| **Meilisearch**                       | https://www.meilisearch.com/docs/learn/what\_is\_meilisearch                             | https://www.meilisearch.com/docs        |
| **Typesense**                         | https://typesense.org/docs/                                                              | https://typesense.org/                  |

### **📊 Big Data Processing**

| **Technology**                | **Best Learning Resource**                                                                                         | **Official Docs**                                     |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------- |
| **Apache Spark**              | https://spark.apache.org/docs/latest/                                                                              | https://spark.apache.org/documentation.html           |
| **Spark - Netflix Use Case**  | https://netflixtechblog.com/notebook-innovation-591ee3221233                                                       | -                                                     |
| **Spark - Uber Use Case**     | https://eng.uber.com/uber-big-data-platform/                                                                       | -                                                     |
| **Apache Hadoop (MapReduce)** | https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html | https://hadoop.apache.org/docs/                       |
| **MapReduce Paper (Google)**  | https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf                    | -                                                     |
| **HDFS**                      | https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html                             | https://hadoop.apache.org/docs/                       |
| **Apache Hive**               | https://hive.apache.org/                                                                                           | https://cwiki.apache.org/confluence/display/Hive/Home |
| **Presto/Trino**              | https://trino.io/docs/current/                                                                                     | https://trino.io/                                     |
| **Presto - Uber Use Case**    | https://eng.uber.com/presto/                                                                                       | -                                                     |
| **Apache Pig**                | https://pig.apache.org/docs/latest/                                                                                | https://pig.apache.org/                               |
| **Databricks**                | https://docs.databricks.com/getting-started/index.html                                                             | https://docs.databricks.com/                          |

### **📈 Analytics & OLAP**

| **Technology**                 | **Best Learning Resource**                                                                                                 | **Official Docs**                     |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| **ClickHouse**                 | https://clickhouse.com/docs/en/intro                                                                                       | https://clickhouse.com/docs           |
| **ClickHouse - Uber Use Case** | https://www.uber.com/blog/logging/                                                                                         | -                                     |
| **Apache Druid**               | https://druid.apache.org/docs/latest/design/                                                                               | https://druid.apache.org/docs/latest/ |
| **Druid - Netflix Use Case**   | https://netflixtechblog.com/how-netflix-uses-druid-for-real-time-insights-to-ensure-a-high-quality-experience-19e1e8568d06 | -                                     |
| **Apache Pinot**               | https://docs.pinot.apache.org/                                                                                             | https://pinot.apache.org/             |
| **Pinot - LinkedIn Use Case**  | https://engineering.linkedin.com/blog/2020/accelerating-data-infrastructure-at-linkedin                                    | -                                     |
| **Snowflake**                  | https://docs.snowflake.com/en/user-guide-intro.html                                                                        | https://docs.snowflake.com/           |
| **BigQuery (Google)**          | https://cloud.google.com/bigquery/docs                                                                                     | https://cloud.google.com/bigquery     |
| **Redshift (AWS)**             | https://aws.amazon.com/redshift/                                                                                           | https://docs.aws.amazon.com/redshift/ |

### **📝 Logging & Monitoring**

| **Technology**                       | **Best Learning Resource**                                                 | **Official Docs**                         |
| ------------------------------------ | -------------------------------------------------------------------------- | ----------------------------------------- |
| **Elasticsearch + Kibana (ELK)**     | https://www.elastic.co/what-is/elk-stack                                   | https://www.elastic.co/guide/index.html   |
| **Kibana**                           | https://www.elastic.co/guide/en/kibana/current/introduction.html           | https://www.elastic.co/kibana             |
| **Logstash**                         | https://www.elastic.co/guide/en/logstash/current/introduction.html         | https://www.elastic.co/logstash           |
| **Grafana**                          | https://grafana.com/docs/grafana/latest/getting-started/                   | https://grafana.com/docs/                 |
| **Prometheus**                       | https://prometheus.io/docs/introduction/overview/                          | https://prometheus.io/docs/               |
| **Prometheus - SoundCloud Use Case** | https://developers.soundcloud.com/blog/prometheus-monitoring-at-soundcloud | -                                         |
| **Datadog**                          | https://docs.datadoghq.com/                                                | https://www.datadoghq.com/                |
| **Splunk**                           | https://docs.splunk.com/Documentation                                      | https://www.splunk.com/                   |
| **Loki (Grafana)**                   | https://grafana.com/docs/loki/latest/                                      | https://grafana.com/oss/loki/             |
| **Jaeger (Distributed Tracing)**     | https://www.jaegertracing.io/docs/1.6/architecture/                        | https://www.jaegertracing.io/docs/        |
| **Zipkin**                           | https://zipkin.io/                                                         | https://zipkin.io/pages/architecture.html |
| **OpenTelemetry**                    | https://opentelemetry.io/docs/                                             | https://opentelemetry.io/                 |

### **🌐 API Gateways & Service Mesh**

| **Technology**      | **Best Learning Resource**                                                                               | **Official Docs**                       |
| ------------------- | -------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| **Kong**            | https://docs.konghq.com/gateway/latest/                                                                  | https://konghq.com/                     |
| **Netflix Zuul**    | https://netflixtechblog.com/zuul-2-the-netflix-journey-to-asynchronous-non-blocking-systems-45947377fb5c | https://github.com/Netflix/zuul         |
| **Envoy**           | https://www.envoyproxy.io/docs/envoy/latest/intro/arch\_overview/arch\_overview                          | https://www.envoyproxy.io/docs          |
| **Istio**           | https://istio.io/latest/docs/concepts/                                                                   | https://istio.io/latest/docs/           |
| **Linkerd**         | https://linkerd.io/2.14/overview/                                                                        | https://linkerd.io/docs/                |
| **Consul**          | https://www.consul.io/docs/architecture                                                                  | https://www.consul.io/                  |
| **AWS API Gateway** | https://aws.amazon.com/api-gateway/                                                                      | https://docs.aws.amazon.com/apigateway/ |
| **NGINX**           | https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/                           | https://nginx.org/en/docs/              |
| **HAProxy**         | https://www.haproxy.com/documentation/hapee/latest/onepage/                                              | https://www.haproxy.org/#docs           |

### **🔄 Workflow Orchestration**

| **Technology**                | **Best Learning Resource**                                                                | **Official Docs**                     |
| ----------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------- |
| **Apache Airflow**            | https://airflow.apache.org/docs/apache-airflow/stable/concepts/index.html                 | https://airflow.apache.org/docs/      |
| **Airflow - Airbnb Use Case** | https://medium.com/airbnb-engineering/airflow-a-workflow-management-platform-46318b977fd8 | -                                     |
| **Temporal**                  | https://docs.temporal.io/concepts                                                         | https://temporal.io/                  |
| **Temporal - Uber Use Case**  | https://www.uber.com/blog/reliable-reprocessing/                                          | -                                     |
| **Apache NiFi**               | https://nifi.apache.org/docs.html                                                         | https://nifi.apache.org/              |
| **Prefect**                   | https://docs.prefect.io/                                                                  | https://www.prefect.io/               |
| **Dagster**                   | https://docs.dagster.io/concepts                                                          | https://dagster.io/                   |
| **Argo Workflows**            | https://argoproj.github.io/argo-workflows/                                                | https://argoproj.github.io/workflows/ |
| **Kubeflow**                  | https://www.kubeflow.org/docs/                                                            | https://www.kubeflow.org/             |

### **🗂️ Object Storage**

| **Technology**                  | **Best Learning Resource**                                                                           | **Official Docs**                         |
| ------------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| **Amazon S3**                   | https://aws.amazon.com/s3/                                                                           | https://docs.aws.amazon.com/s3/           |
| **S3 - Architecture Deep Dive** | https://www.allthingsdistributed.com/2023/07/building-and-operating-a-pretty-big-storage-system.html | -                                         |
| **MinIO**                       | https://min.io/docs/minio/linux/index.html                                                           | https://min.io/                           |
| **Ceph**                        | https://docs.ceph.com/en/latest/architecture/                                                        | https://docs.ceph.com/                    |
| **Azure Blob Storage**          | https://azure.microsoft.com/en-us/services/storage/blobs/                                            | https://docs.microsoft.com/azure/storage/ |
| **Google Cloud Storage**        | https://cloud.google.com/storage/docs                                                                | https://cloud.google.com/storage          |

### **🔐 Distributed Coordination**

| **Technology**            | **Best Learning Resource**                                                                   | **Official Docs**             |
| ------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- |
| **ZooKeeper**             | https://zookeeper.apache.org/doc/current/zookeeperOver.html                                  | https://zookeeper.apache.org/ |
| **Chubby (Google Paper)** | https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf | -                             |
| **etcd**                  | https://etcd.io/docs/v3.5/learning/                                                          | https://etcd.io/              |
| **Consul**                | https://www.consul.io/docs/architecture                                                      | https://www.consul.io/        |

### **🚀 CDN & Edge**

| **Technology**       | **Best Learning Resource**                                                      | **Official Docs**                       |
| -------------------- | ------------------------------------------------------------------------------- | --------------------------------------- |
| **Cloudflare**       | https://blog.cloudflare.com/cloudflare-architecture-and-how-bpf-eats-the-world/ | https://developers.cloudflare.com/      |
| **Akamai**           | https://www.akamai.com/our-thinking/cdn                                         | https://techdocs.akamai.com/            |
| **Fastly**           | https://docs.fastly.com/en/guides/about-fastlys-network                         | https://docs.fastly.com/                |
| **CloudFront (AWS)** | https://aws.amazon.com/cloudfront/                                              | https://docs.aws.amazon.com/cloudfront/ |
| **Varnish Cache**    | https://varnish-cache.org/intro/                                                | https://varnish-cache.org/docs/         |

### **🎯 Feature Flags & A/B Testing**

| **Technology**   | **Best Learning Resource**                         | **Official Docs**           |
| ---------------- | -------------------------------------------------- | --------------------------- |
| **LaunchDarkly** | https://docs.launchdarkly.com/home/getting-started | https://launchdarkly.com/   |
| **Optimizely**   | https://docs.developers.optimizely.com/            | https://www.optimizely.com/ |
| **Split.io**     | https://help.split.io/hc/en-us                     | https://www.split.io/       |
| **Unleash**      | https://docs.getunleash.io/                        | https://www.getunleash.io/  |

### **🤖 ML Infrastructure**

| **Technology**            | **Best Learning Resource**                                                                              | **Official Docs**              |
| ------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------ |
| **TensorFlow Serving**    | https://www.tensorflow.org/tfx/guide/serving                                                            | https://www.tensorflow.org/tfx |
| **MLflow**                | https://mlflow.org/docs/latest/index.html                                                               | https://mlflow.org/            |
| **Kubeflow**              | https://www.kubeflow.org/docs/                                                                          | https://www.kubeflow.org/      |
| **Uber Michelangelo**     | https://eng.uber.com/michelangelo-machine-learning-platform/                                            | -                              |
| **Airbnb Bighead**        | https://medium.com/airbnb-engineering/bighead-airbnbs-end-to-end-machine-learning-platform-f0754450f0a8 | -                              |
| **Ray**                   | https://docs.ray.io/en/latest/                                                                          | https://www.ray.io/            |
| **Feast (Feature Store)** | https://docs.feast.dev/                                                                                 | https://feast.dev/             |

### **📦 Container Orchestration**

| **Technology**   | **Best Learning Resource**            | **Official Docs**                     |
| ---------------- | ------------------------------------- | ------------------------------------- |
| **Kubernetes**   | https://kubernetes.io/docs/concepts/  | https://kubernetes.io/docs/           |
| **Docker**       | https://docs.docker.com/get-started/  | https://docs.docker.com/              |
| **Docker Swarm** | https://docs.docker.com/engine/swarm/ | https://docs.docker.com/engine/swarm/ |
| **Amazon ECS**   | https://aws.amazon.com/ecs/           | https://docs.aws.amazon.com/ecs/      |
| **Nomad**        | https://www.nomadproject.io/docs      | https://www.nomadproject.io/          |

### **🔄 Change Data Capture (CDC)**

| **Technology**    | **Best Learning Resource**                                           | **Official Docs**                               |
| ----------------- | -------------------------------------------------------------------- | ----------------------------------------------- |
| **Debezium**      | https://debezium.io/documentation/reference/stable/architecture.html | https://debezium.io/                            |
| **Maxwell**       | https://maxwells-daemon.io/                                          | https://maxwells-daemon.io/                     |
| **AWS DMS**       | https://aws.amazon.com/dms/                                          | https://docs.aws.amazon.com/dms/                |
| **Kafka Connect** | https://docs.confluent.io/platform/current/connect/index.html        | https://kafka.apache.org/documentation/#connect |

### **⏱️ Time-Series Databases**

| **Technology**      | **Best Learning Resource**                     | **Official Docs**            |
| ------------------- | ---------------------------------------------- | ---------------------------- |
| **InfluxDB**        | https://docs.influxdata.com/influxdb/v2.7/     | https://www.influxdata.com/  |
| **TimescaleDB**     | https://docs.timescale.com/timescaledb/latest/ | https://www.timescale.com/   |
| **Prometheus**      | \[See Monitoring section]                      | -                            |
| **OpenTSDB**        | http://opentsdb.net/docs/build/html/           | http://opentsdb.net/         |
| **VictoriaMetrics** | https://docs.victoriametrics.com/              | https://victoriametrics.com/ |

### **🎬 Media Processing**

| **Technology**       | **Best Learning Resource**                                                    | **Official Docs**                         |
| -------------------- | ----------------------------------------------------------------------------- | ----------------------------------------- |
| **FFmpeg**           | https://ffmpeg.org/ffmpeg.html                                                | https://ffmpeg.org/documentation.html     |
| **GStreamer**        | https://gstreamer.freedesktop.org/documentation/                              | https://gstreamer.freedesktop.org/        |
| **AWS MediaConvert** | https://aws.amazon.com/mediaconvert/                                          | https://docs.aws.amazon.com/mediaconvert/ |
| **Netflix Encoding** | https://netflixtechblog.com/high-quality-video-encoding-at-scale-d159db052746 | -                                         |

***

### **📚 Comparison Resources**

| **Comparison**                      | **Link**                                                              |
| ----------------------------------- | --------------------------------------------------------------------- |
| **Database Comparison (All Types)** | https://db-engines.com/en/ranking                                     |
| **Message Queue Comparison**        | https://www.confluent.io/blog/kafka-fastest-messaging-system/         |
| **Stream Processing Comparison**    | https://www.ververica.com/blog/stream-processing-framework-comparison |
| **Time-Series DB Comparison**       | https://db-engines.com/en/ranking/time+series+dbms                    |
| **Search Engine Comparison**        | https://www.elastic.co/blog/found-elasticsearch-vs-solr               |

***

**This is your complete HLD technology stack reference!** Each technology includes both learning resources and official docs. Start with the use cases from big tech companies to understand WHY each technology exists, then dive into official docs for HOW it works.

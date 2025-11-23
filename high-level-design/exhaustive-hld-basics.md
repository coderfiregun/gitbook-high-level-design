# Exhaustive HLD Basics

## HLD Fundamentals - Complete Prerequisites Checklist

### **🖥️ Operating Systems & Linux Fundamentals**

| **Topic**                   | **Best Resource**                                                 | **Why Critical for HLD**                   |
| --------------------------- | ----------------------------------------------------------------- | ------------------------------------------ |
| **Processes & Threads**     | https://pages.cs.wisc.edu/\~remzi/OSTEP/threads-intro.pdf         | Understanding concurrency, multi-threading |
| **Process Scheduling**      | https://pages.cs.wisc.edu/\~remzi/OSTEP/cpu-sched.pdf             | CPU utilization, load balancing            |
| **Memory Management**       | https://pages.cs.wisc.edu/\~remzi/OSTEP/vm-intro.pdf              | Cache sizing, memory leaks                 |
| **Virtual Memory**          | https://pages.cs.wisc.edu/\~remzi/OSTEP/vm-paging.pdf             | Understanding swap, page faults            |
| **File Systems**            | https://pages.cs.wisc.edu/\~remzi/OSTEP/file-intro.pdf            | Disk I/O, storage systems                  |
| **I/O Systems**             | https://pages.cs.wisc.edu/\~remzi/OSTEP/file-devices.pdf          | Network I/O, blocking vs non-blocking      |
| **Context Switching**       | https://www.geeksforgeeks.org/context-switch-in-operating-system/ | Performance bottlenecks                    |
| **System Calls**            | https://man7.org/linux/man-pages/man2/syscalls.2.html             | How applications interact with OS          |
| **Linux Performance Tools** | https://www.brendangregg.com/linuxperf.html                       | Debugging production issues                |

### **🌐 Computer Networks**

| **Topic**                  | **Best Resource**                                                                         | **Why Critical for HLD**     |
| -------------------------- | ----------------------------------------------------------------------------------------- | ---------------------------- |
| **OSI Model**              | https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/ | Understanding network layers |
| **TCP/IP Deep Dive**       | https://www.rfc-editor.org/rfc/rfc793                                                     | Reliable communication       |
| **TCP vs UDP**             | https://www.cloudflare.com/learning/ddos/glossary/tcp-ip/                                 | When to use which protocol   |
| **HTTP/HTTPS**             | https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview                                | Web communication            |
| **HTTP/2 vs HTTP/3**       | https://www.cloudflare.com/learning/performance/http2-vs-http1.1/                         | Modern web protocols         |
| **WebSockets**             | https://developer.mozilla.org/en-US/docs/Web/API/WebSockets\_API                          | Real-time communication      |
| **gRPC**                   | https://grpc.io/docs/what-is-grpc/introduction/                                           | Microservices communication  |
| **DNS**                    | https://www.cloudflare.com/learning/dns/what-is-dns/                                      | Domain name resolution       |
| **Load Balancing**         | https://www.nginx.com/resources/glossary/load-balancing/                                  | Traffic distribution         |
| **CDN**                    | https://www.cloudflare.com/learning/cdn/what-is-a-cdn/                                    | Content delivery             |
| **SSL/TLS**                | https://www.cloudflare.com/learning/ssl/what-is-ssl/                                      | Secure communication         |
| **TCP Handshake**          | https://www.cloudflare.com/learning/ddos/glossary/tcp-ip/                                 | Connection establishment     |
| **Network Latency**        | https://www.cloudflare.com/learning/performance/glossary/what-is-latency/                 | Performance optimization     |
| **NAT**                    | https://www.cloudflare.com/learning/network-layer/what-is-nat/                            | IP address translation       |
| **Proxy vs Reverse Proxy** | https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/                           | Architecture patterns        |

### **💾 Database Fundamentals**

| **Topic**                           | **Best Resource**                                              | **Why Critical for HLD**       |
| ----------------------------------- | -------------------------------------------------------------- | ------------------------------ |
| **ACID Properties**                 | https://www.databricks.com/glossary/acid-transactions          | Transaction guarantees         |
| **CAP Theorem**                     | https://www.ibm.com/topics/cap-theorem                         | Distributed systems trade-offs |
| **Normalization**                   | https://www.guru99.com/database-normalization.html             | Schema design                  |
| **Indexes (B-Tree, Hash)**          | https://use-the-index-luke.com/                                | Query performance              |
| **Database Sharding**               | https://www.mongodb.com/features/database-sharding-explained   | Horizontal scaling             |
| **Replication**                     | https://aws.amazon.com/rds/features/read-replicas/             | High availability              |
| **SQL vs NoSQL**                    | https://www.mongodb.com/nosql-explained/nosql-vs-sql           | When to use which              |
| **Transactions & Isolation Levels** | https://www.postgresql.org/docs/current/transaction-iso.html   | Consistency guarantees         |
| **Query Optimization**              | https://use-the-index-luke.com/sql/preface                     | Performance tuning             |
| **Connection Pooling**              | https://www.cockroachlabs.com/blog/what-is-connection-pooling/ | Resource management            |
| **Database Locks**                  | https://www.postgresql.org/docs/current/explicit-locking.html  | Concurrency control            |
| **Write-Ahead Logging (WAL)**       | https://www.postgresql.org/docs/current/wal-intro.html         | Durability                     |
| **MVCC**                            | https://www.postgresql.org/docs/current/mvcc-intro.html        | Concurrency without locks      |

### **🔄 Distributed Systems Concepts**

| **Topic**                     | **Best Resource**                                                            | **Why Critical for HLD**  |
| ----------------------------- | ---------------------------------------------------------------------------- | ------------------------- |
| **Consistency Models**        | https://jepsen.io/consistency                                                | Understanding guarantees  |
| **Eventual Consistency**      | https://www.allthingsdistributed.com/2008/12/eventually\_consistent.html     | NoSQL databases           |
| **Strong Consistency**        | https://aphyr.com/posts/313-strong-consistency-models                        | ACID guarantees           |
| **Distributed Transactions**  | https://www.cockroachlabs.com/blog/living-without-atomic-clocks/             | Cross-service operations  |
| **Two-Phase Commit (2PC)**    | https://en.wikipedia.org/wiki/Two-phase\_commit\_protocol                    | Coordinated commits       |
| **Saga Pattern**              | https://microservices.io/patterns/data/saga.html                             | Long-running transactions |
| **Consensus (Paxos, Raft)**   | https://raft.github.io/                                                      | Leader election           |
| **Vector Clocks**             | https://riak.com/posts/technical/vector-clocks-revisited/index.html          | Causality tracking        |
| **Gossip Protocol**           | https://www.consul.io/docs/architecture/gossip                               | Cluster membership        |
| **Quorum**                    | https://www.mongodb.com/basics/what-is-quorum                                | Write/read consistency    |
| **Split Brain**               | https://www.cockroachlabs.com/blog/trust-but-verify-cockroachdb-replication/ | Network partitions        |
| **Byzantine Fault Tolerance** | https://pmg.csail.mit.edu/papers/osdi99.pdf                                  | Malicious failures        |
| **Distributed Locks**         | https://redis.io/docs/manual/patterns/distributed-locks/                     | Coordination              |
| **Clock Synchronization**     | https://cloud.google.com/spanner/docs/true-time-external-consistency         | Distributed timing        |

### **🏗️ System Design Fundamentals**

| **Topic**                                | **Best Resource**                                                                     | **Why Critical for HLD** |
| ---------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------ |
| **Scalability (Vertical vs Horizontal)** | https://www.nginx.com/blog/scaling-web-applications-horizontal-vs-vertical-scaling/   | Growth strategies        |
| **Availability**                         | https://landing.google.com/sre/sre-book/chapters/availability-table/                  | Uptime guarantees        |
| **Reliability**                          | https://sre.google/sre-book/embracing-risk/                                           | System dependability     |
| **Fault Tolerance**                      | https://aws.amazon.com/builders-library/avoiding-fallback-in-distributed-systems/     | Handling failures        |
| **Latency vs Throughput**                | https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/     | Performance metrics      |
| **Back-of-the-envelope Calculations**    | https://github.com/donnemartin/system-design-primer#back-of-the-envelope-calculations | Capacity planning        |
| **Single Point of Failure (SPOF)**       | https://aws.amazon.com/builders-library/static-stability-using-availability-zones/    | Reliability design       |
| **Circuit Breaker Pattern**              | https://martinfowler.com/bliki/CircuitBreaker.html                                    | Fault isolation          |
| **Bulkhead Pattern**                     | https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead                 | Resource isolation       |
| **Rate Limiting**                        | https://stripe.com/blog/rate-limiters                                                 | Preventing abuse         |
| **Retry Logic & Exponential Backoff**    | https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/     | Resilient systems        |
| **Idempotency**                          | https://stripe.com/blog/idempotency                                                   | Safe retries             |
| **API Design (REST, GraphQL)**           | https://cloud.google.com/apis/design                                                  | Interface contracts      |
| **Pagination**                           | https://www.citusdata.com/blog/2016/03/30/five-ways-to-paginate/                      | Large dataset handling   |

### **🗄️ Caching Strategies**

| **Topic**                              | **Best Resource**                                                        | **Why Critical for HLD**   |
| -------------------------------------- | ------------------------------------------------------------------------ | -------------------------- |
| **Cache Fundamentals**                 | https://redis.io/docs/manual/patterns/caching/                           | Performance optimization   |
| **Cache Eviction Policies (LRU, LFU)** | https://redis.io/docs/manual/eviction/                                   | Memory management          |
| **Cache-Aside Pattern**                | https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside | Application caching        |
| **Write-Through Cache**                | https://redis.io/docs/manual/patterns/write-through/                     | Consistency                |
| **Write-Behind Cache**                 | https://hazelcast.com/glossary/write-through-write-back-cache/           | Performance                |
| **Cache Invalidation**                 | https://martinfowler.com/bliki/TwoHardThings.html                        | Data freshness             |
| **Cache Stampede**                     | https://en.wikipedia.org/wiki/Cache\_stampede                            | Preventing thundering herd |
| **CDN Caching**                        | https://www.cloudflare.com/learning/cdn/what-is-caching/                 | Edge caching               |

### **📨 Message Queues & Async Processing**

| **Topic**                                     | **Best Resource**                                                                                   | **Why Critical for HLD**  |
| --------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------- |
| **Message Queue Basics**                      | https://aws.amazon.com/message-queue/                                                               | Decoupling services       |
| **Pub/Sub Pattern**                           | https://cloud.google.com/pubsub/docs/overview                                                       | Event-driven architecture |
| **At-Most-Once, At-Least-Once, Exactly-Once** | https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/   | Delivery guarantees       |
| **Dead Letter Queue**                         | https://aws.amazon.com/what-is/dead-letter-queue/                                                   | Error handling            |
| **Message Ordering**                          | https://www.confluent.io/blog/apache-kafka-producer-improvements-sticky-partitioner/                | Sequence guarantees       |
| **Backpressure**                              | https://medium.com/@jayphelps/backpressure-explained-the-flow-of-data-through-software-2350b3e77ce7 | Flow control              |
| **Event Sourcing**                            | https://martinfowler.com/eaaDev/EventSourcing.html                                                  | Audit trail               |
| **CQRS**                                      | https://martinfowler.com/bliki/CQRS.html                                                            | Read/write separation     |

### **🐳 Containers & Orchestration (Kubernetes)**

| **Topic**                              | **Best Resource**                                                                                     | **Why Critical for HLD** |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------ |
| **Docker Basics**                      | https://docs.docker.com/get-started/                                                                  | Containerization         |
| **Container Images & Layers**          | https://docs.docker.com/storage/storagedriver/                                                        | Image optimization       |
| **Container Networking**               | https://docs.docker.com/network/                                                                      | Service communication    |
| **Kubernetes Architecture**            | https://kubernetes.io/docs/concepts/overview/components/                                              | Orchestration platform   |
| **Pods**                               | https://kubernetes.io/docs/concepts/workloads/pods/                                                   | Basic deployment unit    |
| **Services**                           | https://kubernetes.io/docs/concepts/services-networking/service/                                      | Service discovery        |
| **Ingress**                            | https://kubernetes.io/docs/concepts/services-networking/ingress/                                      | External access          |
| **Egress**                             | https://kubernetes.io/docs/concepts/services-networking/network-policies/                             | Outbound traffic control |
| **ConfigMaps & Secrets**               | https://kubernetes.io/docs/concepts/configuration/configmap/                                          | Configuration management |
| **Deployments**                        | https://kubernetes.io/docs/concepts/workloads/controllers/deployment/                                 | Rolling updates          |
| **StatefulSets**                       | https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/                                | Stateful applications    |
| **DaemonSets**                         | https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/                                  | Node-level services      |
| **Horizontal Pod Autoscaler**          | https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/                            | Auto-scaling             |
| **Resource Limits**                    | https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/                        | Resource management      |
| **Health Checks (Liveness/Readiness)** | https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/ | Service reliability      |
| **Service Mesh (Istio)**               | https://istio.io/latest/docs/concepts/what-is-istio/                                                  | Advanced networking      |
| **Sidecars & Init Containers**         | https://kubernetes.io/docs/concepts/workloads/pods/init-containers/                                   | Supporting containers    |
| **Namespaces**                         | https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/                         | Resource isolation       |
| **RBAC**                               | https://kubernetes.io/docs/reference/access-authn-authz/rbac/                                         | Access control           |

### **🌐 Web Server & Proxies**

| **Topic**                          | **Best Resource**                                                                     | **Why Critical for HLD**     |
| ---------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------- |
| **NGINX Basics**                   | https://www.nginx.com/resources/glossary/nginx/                                       | Reverse proxy, load balancer |
| **NGINX Configuration**            | https://nginx.org/en/docs/beginners\_guide.html                                       | Web server setup             |
| **Forward Proxy vs Reverse Proxy** | https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/                       | Architecture patterns        |
| **Load Balancing Algorithms**      | https://www.nginx.com/blog/choosing-nginx-plus-load-balancing-techniques/             | Traffic distribution         |
| **SSL Termination**                | https://www.nginx.com/blog/nginx-ssl/                                                 | Security layer               |
| **Connection Pooling**             | https://www.nginx.com/blog/tuning-nginx/                                              | Resource efficiency          |
| **Rate Limiting (NGINX)**          | https://www.nginx.com/blog/rate-limiting-nginx/                                       | Traffic control              |
| **HAProxy**                        | https://www.haproxy.com/blog/the-four-essential-sections-of-an-haproxy-configuration/ | High-performance LB          |

### **🔐 Security Fundamentals**

| **Topic**                           | **Best Resource**                                                                                          | **Why Critical for HLD** |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------ |
| **Authentication vs Authorization** | https://auth0.com/docs/get-started/identity-fundamentals/authentication-and-authorization                  | User security            |
| **OAuth 2.0**                       | https://oauth.net/2/                                                                                       | Delegated authorization  |
| **JWT**                             | https://jwt.io/introduction                                                                                | Stateless auth           |
| **API Keys**                        | https://cloud.google.com/endpoints/docs/openapi/when-why-api-key                                           | Simple authentication    |
| **HTTPS/TLS**                       | https://www.cloudflare.com/learning/ssl/what-is-ssl/                                                       | Encrypted communication  |
| **CORS**                            | https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS                                                     | Cross-origin requests    |
| **CSRF Protection**                 | https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site\_Request\_Forgery\_Prevention\_Cheat\_Sheet.html | Attack prevention        |
| **XSS Prevention**                  | https://cheatsheetseries.owasp.org/cheatsheets/Cross\_Site\_Scripting\_Prevention\_Cheat\_Sheet.html       | Input sanitization       |
| **SQL Injection Prevention**        | https://cheatsheetseries.owasp.org/cheatsheets/SQL\_Injection\_Prevention\_Cheat\_Sheet.html               | Query security           |
| **Rate Limiting & DDoS**            | https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/                                            | Attack mitigation        |
| **Encryption at Rest**              | https://aws.amazon.com/what-is/data-encryption/                                                            | Data security            |
| **Zero Trust Architecture**         | https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/                                  | Modern security model    |

### **📊 Monitoring & Observability**

| **Topic**                                    | **Best Resource**                                                              | **Why Critical for HLD** |
| -------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------ |
| **Logging**                                  | https://www.datadoghq.com/knowledge-center/logging/                            | Debugging                |
| **Metrics**                                  | https://grafana.com/docs/grafana/latest/fundamentals/intro-to-metrics/         | Performance tracking     |
| **Tracing**                                  | https://www.jaegertracing.io/docs/1.6/architecture/                            | Request flow             |
| **SLI, SLO, SLA**                            | https://sre.google/sre-book/service-level-objectives/                          | Reliability targets      |
| **Error Budgets**                            | https://sre.google/workbook/implementing-slos/                                 | Risk management          |
| **Alerting**                                 | https://prometheus.io/docs/practices/alerting/                                 | Incident response        |
| **APM (Application Performance Monitoring)** | https://www.datadoghq.com/knowledge-center/application-performance-monitoring/ | End-to-end visibility    |

### **🔧 Data Structures & Algorithms for HLD**

| **Topic**              | **Best Resource**                                                                   | **Why Critical for HLD**    |
| ---------------------- | ----------------------------------------------------------------------------------- | --------------------------- |
| **Hash Tables**        | https://www.geeksforgeeks.org/hashing-data-structure/                               | O(1) lookups, caching       |
| **Consistent Hashing** | https://www.toptal.com/big-data/consistent-hashing                                  | Distributed caching         |
| **B-Trees**            | https://www.geeksforgeeks.org/introduction-of-b-tree-2/                             | Database indexes            |
| **LSM Trees**          | https://www.cs.umb.edu/\~poneil/lsmtree.pdf                                         | Write-optimized storage     |
| **Bloom Filters**      | https://www.geeksforgeeks.org/bloom-filters-introduction-and-python-implementation/ | Membership testing          |
| **Trie**               | https://www.geeksforgeeks.org/trie-insert-and-search/                               | Autocomplete, prefix search |
| **Skip Lists**         | https://www.geeksforgeeks.org/skip-list/                                            | Sorted data structure       |
| **HyperLogLog**        | https://redis.io/docs/data-types/probabilistic/hyperloglogs/                        | Cardinality estimation      |
| **Geohashing**         | https://www.geeksforgeeks.org/geohashing-in-python/                                 | Location indexing           |
| **Merkle Trees**       | https://www.geeksforgeeks.org/introduction-to-merkle-tree/                          | Data verification           |

### **📐 Capacity Planning**

| **Topic**                    | **Best Resource**                                                                                | **Why Critical for HLD** |
| ---------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------ |
| **QPS (Queries Per Second)** | https://github.com/donnemartin/system-design-primer#step-2-sketch-up-a-high-level-design         | Load estimation          |
| **Bandwidth Calculation**    | https://github.com/donnemartin/system-design-primer#latency-numbers-every-programmer-should-know | Network requirements     |
| **Storage Estimation**       | https://github.com/donnemartin/system-design-primer#step-3-design-core-components                | Disk planning            |
| **Memory Estimation**        | https://github.com/donnemartin/system-design-primer#step-2-sketch-up-a-high-level-design         | RAM requirements         |
| **Latency Numbers**          | https://gist.github.com/jboner/2841832                                                           | Performance expectations |
| **Powers of Two**            | https://github.com/donnemartin/system-design-primer#powers-of-two-table                          | Quick calculations       |

### **🎯 Architecture Patterns**

| **Topic**                         | **Best Resource**                                                  | **Why Critical for HLD** |
| --------------------------------- | ------------------------------------------------------------------ | ------------------------ |
| **Microservices**                 | https://martinfowler.com/articles/microservices.html               | Service decomposition    |
| **Monolith**                      | https://martinfowler.com/bliki/MonolithFirst.html                  | When to use              |
| **Service-Oriented Architecture** | https://www.ibm.com/topics/soa                                     | Enterprise patterns      |
| **Event-Driven Architecture**     | https://martinfowler.com/articles/201701-event-driven.html         | Async systems            |
| **Lambda Architecture**           | https://www.databricks.com/glossary/lambda-architecture            | Batch + real-time        |
| **Kappa Architecture**            | https://www.oreilly.com/radar/questioning-the-lambda-architecture/ | Stream-only processing   |
| **Strangler Fig Pattern**         | https://martinfowler.com/bliki/StranglerFigApplication.html        | Migration strategy       |
| **API Gateway Pattern**           | https://microservices.io/patterns/apigateway.html                  | Single entry point       |
| **Backend for Frontend (BFF)**    | https://samnewman.io/patterns/architectural/bff/                   | Client-specific APIs     |

### **📖 Essential Books**

| **Book**                                  | **Link**                                       | **What You'll Learn**         |
| ----------------------------------------- | ---------------------------------------------- | ----------------------------- |
| **Designing Data-Intensive Applications** | https://dataintensive.net/                     | Distributed systems bible     |
| **System Design Interview Vol 1 & 2**     | Amazon (Alex Xu)                               | Interview prep + fundamentals |
| **Google SRE Book**                       | https://sre.google/books/                      | Production operations         |
| **Database Internals**                    | https://www.databass.dev/                      | How databases work            |
| **Kubernetes in Action**                  | Manning                                        | K8s deep dive                 |
| **Site Reliability Engineering**          | https://sre.google/sre-book/table-of-contents/ | Reliability principles        |

### **🎓 Study Path (8-Week Plan)**

| **Week**   | **Focus Area**                           | **Time Investment** |
| ---------- | ---------------------------------------- | ------------------- |
| **Week 1** | OS, Networking Basics                    | 15-20 hours         |
| **Week 2** | Database Fundamentals, SQL               | 15-20 hours         |
| **Week 3** | Distributed Systems Concepts             | 20-25 hours         |
| **Week 4** | Caching, Message Queues                  | 15-20 hours         |
| **Week 5** | Docker, Kubernetes                       | 20-25 hours         |
| **Week 6** | Web Servers, Load Balancers              | 15-20 hours         |
| **Week 7** | Monitoring, Security                     | 15-20 hours         |
| **Week 8** | Architecture Patterns, Capacity Planning | 20-25 hours         |

***

**Start with these fundamentals before diving into specific system design problems. Master these and you'll understand WHY systems are designed the way they are, not just HOW to design them!**

# 🏗️ System Design Concepts Sheet

A structured checklist of the core concepts, patterns, and case studies for system design interviews — organized into **15 topic-wise sections**, from fundamentals to full end-to-end designs.

**Legend:** 🟢 Core &nbsp;·&nbsp; 🟡 Intermediate &nbsp;·&nbsp; 🔴 Advanced

---

## 📊 Overview

**137 concepts** &nbsp;·&nbsp; 🟢 **36** Core &nbsp;·&nbsp; 🟡 **68** Intermediate &nbsp;·&nbsp; 🔴 **33** Advanced

Check off a box as you learn each concept — GitHub renders these as interactive checkboxes.

---

## 📑 Table of Contents

| # | Section | Concepts | 🟢 | 🟡 | 🔴 |
| --- | --- | :---: | :---: | :---: | :---: |
| 1 | [Fundamentals & Estimation](#1-fundamentals-estimation) | 9 | 7 | 2 | 0 |
| 2 | [Networking & Communication](#2-networking-communication) | 10 | 5 | 5 | 0 |
| 3 | [API Design & Communication Styles](#3-api-design-communication-styles) | 9 | 3 | 6 | 0 |
| 4 | [Databases & Storage](#4-databases-storage) | 10 | 4 | 4 | 2 |
| 5 | [Caching](#5-caching) | 8 | 1 | 5 | 2 |
| 6 | [Scalability & Load Balancing](#6-scalability-load-balancing) | 7 | 2 | 4 | 1 |
| 7 | [Consistency, Availability & Consensus](#7-consistency-availability-consensus) | 10 | 1 | 2 | 7 |
| 8 | [Messaging & Event-Driven Systems](#8-messaging-event-driven-systems) | 9 | 1 | 5 | 3 |
| 9 | [Reliability & Fault Tolerance](#9-reliability-fault-tolerance) | 9 | 2 | 4 | 3 |
| 10 | [Architecture Patterns](#10-architecture-patterns) | 8 | 2 | 3 | 3 |
| 11 | [Security](#11-security) | 9 | 3 | 6 | 0 |
| 12 | [Observability & Operations](#12-observability-operations) | 9 | 4 | 5 | 0 |
| 13 | [Big Data & Search](#13-big-data-search) | 8 | 0 | 4 | 4 |
| 14 | [Design Building Blocks](#14-design-building-blocks) | 8 | 0 | 5 | 3 |
| 15 | [System Design Case Studies](#15-system-design-case-studies) | 14 | 1 | 8 | 5 |

---

## 1. Fundamentals & Estimation
<sub>9 concepts &nbsp;·&nbsp; 🟢 7 · 🟡 2</sub>

- [ ] 🟢 Client–Server Model <sub>`Core`</sub>
- [ ] 🟢 Latency, Throughput & Bandwidth <sub>`Core`</sub>
- [ ] 🟢 Back-of-the-Envelope Estimation <sub>`Core`</sub>
- [ ] 🟢 Vertical vs Horizontal Scaling <sub>`Core`</sub>
- [ ] 🟢 Availability, SLA / SLO / SLI <sub>`Core`</sub>
- [ ] 🟢 Functional vs Non-Functional Requirements <sub>`Core`</sub>
- [ ] 🟢 Latency Numbers Every Engineer Should Know <sub>`Core`</sub>
- [ ] 🟡 Single Point of Failure (SPOF) <sub>`Intermediate`</sub>
- [ ] 🟡 Proxy vs Reverse Proxy <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 2. Networking & Communication
<sub>10 concepts &nbsp;·&nbsp; 🟢 5 · 🟡 5</sub>

- [ ] 🟢 OSI & TCP/IP Model <sub>`Core`</sub>
- [ ] 🟢 TCP vs UDP <sub>`Core`</sub>
- [ ] 🟢 HTTP / HTTPS <sub>`Core`</sub>
- [ ] 🟡 HTTP/2 & HTTP/3 (QUIC) <sub>`Intermediate`</sub>
- [ ] 🟢 DNS & Resolution Flow <sub>`Core`</sub>
- [ ] 🟢 IP Addressing & Ports <sub>`Core`</sub>
- [ ] 🟡 WebSockets <sub>`Intermediate`</sub>
- [ ] 🟡 Long Polling vs SSE vs WebSockets <sub>`Intermediate`</sub>
- [ ] 🟡 Content Delivery Network (CDN) <sub>`Intermediate`</sub>
- [ ] 🟡 gRPC & Protocol Buffers <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 3. API Design & Communication Styles
<sub>9 concepts &nbsp;·&nbsp; 🟢 3 · 🟡 6</sub>

- [ ] 🟢 REST Principles <sub>`Core`</sub>
- [ ] 🟡 GraphQL <sub>`Intermediate`</sub>
- [ ] 🟡 RPC / gRPC <sub>`Intermediate`</sub>
- [ ] 🟡 API Gateway <sub>`Intermediate`</sub>
- [ ] 🟡 Rate Limiting & Throttling <sub>`Intermediate`</sub>
- [ ] 🟡 Idempotency <sub>`Intermediate`</sub>
- [ ] 🟢 Pagination <sub>`Core`</sub>
- [ ] 🟡 Webhooks <sub>`Intermediate`</sub>
- [ ] 🟢 API Versioning <sub>`Core`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 4. Databases & Storage
<sub>10 concepts &nbsp;·&nbsp; 🟢 4 · 🟡 4 · 🔴 2</sub>

- [ ] 🟢 SQL vs NoSQL <sub>`Core`</sub>
- [ ] 🟢 Relational Databases & ACID <sub>`Core`</sub>
- [ ] 🟡 Key-Value / Document / Column / Graph Stores <sub>`Intermediate`</sub>
- [ ] 🟡 Indexing (B-Tree, Hash, LSM) <sub>`Intermediate`</sub>
- [ ] 🟢 Normalization vs Denormalization <sub>`Core`</sub>
- [ ] 🟡 Replication (Leader-Follower, Multi-Leader) <sub>`Intermediate`</sub>
- [ ] 🔴 Sharding & Partitioning <sub>`Advanced`</sub>
- [ ] 🔴 Federation <sub>`Advanced`</sub>
- [ ] 🟢 Blob / Object Storage <sub>`Core`</sub>
- [ ] 🟡 Data Warehouse vs Data Lake <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 5. Caching
<sub>8 concepts &nbsp;·&nbsp; 🟢 1 · 🟡 5 · 🔴 2</sub>

- [ ] 🟢 Caching Fundamentals <sub>`Core`</sub>
- [ ] 🟡 Cache-Aside / Read-Through <sub>`Intermediate`</sub>
- [ ] 🟡 Write-Through / Write-Back / Write-Around <sub>`Intermediate`</sub>
- [ ] 🟡 Eviction Policies (LRU, LFU, FIFO) <sub>`Intermediate`</sub>
- [ ] 🟡 Redis vs Memcached <sub>`Intermediate`</sub>
- [ ] 🟡 CDN & Edge Caching <sub>`Intermediate`</sub>
- [ ] 🔴 Cache Invalidation <sub>`Advanced`</sub>
- [ ] 🔴 Cache Stampede / Thundering Herd <sub>`Advanced`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 6. Scalability & Load Balancing
<sub>7 concepts &nbsp;·&nbsp; 🟢 2 · 🟡 4 · 🔴 1</sub>

- [ ] 🟢 Load Balancer <sub>`Core`</sub>
- [ ] 🟡 LB Algorithms (Round Robin, Least Connections) <sub>`Intermediate`</sub>
- [ ] 🟡 Layer 4 vs Layer 7 Load Balancing <sub>`Intermediate`</sub>
- [ ] 🟢 Stateless Services & Horizontal Scaling <sub>`Core`</sub>
- [ ] 🟡 Auto-Scaling <sub>`Intermediate`</sub>
- [ ] 🔴 Consistent Hashing <sub>`Advanced`</sub>
- [ ] 🟡 Database Connection Pooling <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 7. Consistency, Availability & Consensus
<sub>10 concepts &nbsp;·&nbsp; 🟢 1 · 🟡 2 · 🔴 7</sub>

- [ ] 🟢 CAP Theorem <sub>`Core`</sub>
- [ ] 🔴 PACELC Theorem <sub>`Advanced`</sub>
- [ ] 🟡 Strong vs Eventual Consistency <sub>`Intermediate`</sub>
- [ ] 🟡 ACID vs BASE <sub>`Intermediate`</sub>
- [ ] 🔴 Quorum (R + W > N) <sub>`Advanced`</sub>
- [ ] 🔴 Consensus: Paxos & Raft <sub>`Advanced`</sub>
- [ ] 🔴 Leader Election <sub>`Advanced`</sub>
- [ ] 🔴 Two-Phase Commit (2PC) <sub>`Advanced`</sub>
- [ ] 🔴 Saga Pattern <sub>`Advanced`</sub>
- [ ] 🔴 Vector Clocks & Conflict Resolution <sub>`Advanced`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 8. Messaging & Event-Driven Systems
<sub>9 concepts &nbsp;·&nbsp; 🟢 1 · 🟡 5 · 🔴 3</sub>

- [ ] 🟢 Message Queues <sub>`Core`</sub>
- [ ] 🟡 Publish–Subscribe <sub>`Intermediate`</sub>
- [ ] 🟡 Apache Kafka <sub>`Intermediate`</sub>
- [ ] 🟡 RabbitMQ / SQS <sub>`Intermediate`</sub>
- [ ] 🟡 Event-Driven Architecture <sub>`Intermediate`</sub>
- [ ] 🔴 Stream Processing <sub>`Advanced`</sub>
- [ ] 🟡 Dead Letter Queue <sub>`Intermediate`</sub>
- [ ] 🔴 Backpressure <sub>`Advanced`</sub>
- [ ] 🔴 Delivery Semantics (At-least / Exactly-once) <sub>`Advanced`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 9. Reliability & Fault Tolerance
<sub>9 concepts &nbsp;·&nbsp; 🟢 2 · 🟡 4 · 🔴 3</sub>

- [ ] 🟢 Redundancy & Replication <sub>`Core`</sub>
- [ ] 🟡 Failover <sub>`Intermediate`</sub>
- [ ] 🟡 Circuit Breaker <sub>`Intermediate`</sub>
- [ ] 🟡 Retries, Timeouts & Exponential Backoff <sub>`Intermediate`</sub>
- [ ] 🔴 Bulkhead Pattern <sub>`Advanced`</sub>
- [ ] 🟡 Graceful Degradation <sub>`Intermediate`</sub>
- [ ] 🔴 Disaster Recovery (RTO / RPO) <sub>`Advanced`</sub>
- [ ] 🟢 Health Checks & Heartbeats <sub>`Core`</sub>
- [ ] 🔴 Chaos Engineering <sub>`Advanced`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 10. Architecture Patterns
<sub>8 concepts &nbsp;·&nbsp; 🟢 2 · 🟡 3 · 🔴 3</sub>

- [ ] 🟢 Monolith vs Microservices <sub>`Core`</sub>
- [ ] 🟢 N-Tier / Layered Architecture <sub>`Core`</sub>
- [ ] 🟡 Service-Oriented Architecture (SOA) <sub>`Intermediate`</sub>
- [ ] 🟡 Serverless / FaaS <sub>`Intermediate`</sub>
- [ ] 🔴 Event Sourcing <sub>`Advanced`</sub>
- [ ] 🔴 CQRS <sub>`Advanced`</sub>
- [ ] 🔴 Sidecar & Service Mesh <sub>`Advanced`</sub>
- [ ] 🟡 Strangler Fig (Migration) <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 11. Security
<sub>9 concepts &nbsp;·&nbsp; 🟢 3 · 🟡 6</sub>

- [ ] 🟢 Authentication vs Authorization <sub>`Core`</sub>
- [ ] 🟡 OAuth 2.0 & OpenID Connect <sub>`Intermediate`</sub>
- [ ] 🟡 JWT vs Sessions <sub>`Intermediate`</sub>
- [ ] 🟢 TLS / SSL & HTTPS <sub>`Core`</sub>
- [ ] 🟡 Encryption at Rest & in Transit <sub>`Intermediate`</sub>
- [ ] 🟢 Hashing & Salting <sub>`Core`</sub>
- [ ] 🟡 Secrets Management & API Keys <sub>`Intermediate`</sub>
- [ ] 🟡 DDoS Protection & WAF <sub>`Intermediate`</sub>
- [ ] 🟡 OWASP Top 10 <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 12. Observability & Operations
<sub>9 concepts &nbsp;·&nbsp; 🟢 4 · 🟡 5</sub>

- [ ] 🟢 Logging <sub>`Core`</sub>
- [ ] 🟢 Metrics & Monitoring <sub>`Core`</sub>
- [ ] 🟡 Distributed Tracing <sub>`Intermediate`</sub>
- [ ] 🟢 Alerting <sub>`Core`</sub>
- [ ] 🟡 Application Performance Monitoring (APM) <sub>`Intermediate`</sub>
- [ ] 🟡 Deployment Strategies (Blue-Green, Canary, Rolling) <sub>`Intermediate`</sub>
- [ ] 🟢 CI/CD Pipelines <sub>`Core`</sub>
- [ ] 🟡 Feature Flags <sub>`Intermediate`</sub>
- [ ] 🟡 Infrastructure as Code <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 13. Big Data & Search
<sub>8 concepts &nbsp;·&nbsp; 🟡 4 · 🔴 4</sub>

- [ ] 🔴 MapReduce <sub>`Advanced`</sub>
- [ ] 🟡 Batch vs Stream Processing <sub>`Intermediate`</sub>
- [ ] 🟡 Full-Text Search / Elasticsearch <sub>`Intermediate`</sub>
- [ ] 🟡 Data Pipelines (ETL / ELT) <sub>`Intermediate`</sub>
- [ ] 🔴 Bloom Filters <sub>`Advanced`</sub>
- [ ] 🔴 HyperLogLog <sub>`Advanced`</sub>
- [ ] 🔴 Count-Min Sketch <sub>`Advanced`</sub>
- [ ] 🟡 Time-Series Databases <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 14. Design Building Blocks
<sub>8 concepts &nbsp;·&nbsp; 🟡 5 · 🔴 3</sub>

- [ ] 🟡 Unique ID Generation (Snowflake) <sub>`Intermediate`</sub>
- [ ] 🔴 Distributed Locking <sub>`Advanced`</sub>
- [ ] 🔴 Geohashing & Quadtrees <sub>`Advanced`</sub>
- [ ] 🟡 Rate Limiter Design <sub>`Intermediate`</sub>
- [ ] 🟡 Notification / Fan-out <sub>`Intermediate`</sub>
- [ ] 🔴 Distributed Job Scheduler <sub>`Advanced`</sub>
- [ ] 🟡 Config & Service Discovery <sub>`Intermediate`</sub>
- [ ] 🟡 Idempotency Keys <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 15. System Design Case Studies
<sub>14 concepts &nbsp;·&nbsp; 🟢 1 · 🟡 8 · 🔴 5</sub>

- [ ] 🟢 Design a URL Shortener (TinyURL) <sub>`Core`</sub>
- [ ] 🟡 Design a Rate Limiter <sub>`Intermediate`</sub>
- [ ] 🔴 Design a Distributed Key-Value Store <sub>`Advanced`</sub>
- [ ] 🟡 Design a News Feed (Twitter/Facebook) <sub>`Intermediate`</sub>
- [ ] 🟡 Design a Chat System (WhatsApp) <sub>`Intermediate`</sub>
- [ ] 🟡 Design a Web Crawler <sub>`Intermediate`</sub>
- [ ] 🟡 Design a Notification System <sub>`Intermediate`</sub>
- [ ] 🔴 Design Video Streaming (YouTube/Netflix) <sub>`Advanced`</sub>
- [ ] 🔴 Design Ride-Sharing (Uber/Lyft) <sub>`Advanced`</sub>
- [ ] 🟡 Design Search Autocomplete / Typeahead <sub>`Intermediate`</sub>
- [ ] 🔴 Design Cloud File Storage (Dropbox/Drive) <sub>`Advanced`</sub>
- [ ] 🟡 Design a Ticketing System (Ticketmaster) <sub>`Intermediate`</sub>
- [ ] 🔴 Design a Payment System <sub>`Advanced`</sub>
- [ ] 🟡 Design a Leaderboard <sub>`Intermediate`</sub>

<div align="right"><a href="#-table-of-contents">⬆ back to top</a></div>

---

## 📚 Recommended Resources

- [System Design Primer](https://github.com/donnemartin/system-design-primer) — the canonical open-source study guide
- [System Design (karanpratapsingh)](https://github.com/karanpratapsingh/system-design) — concise concept-by-concept notes
- [ByteByteGo](https://bytebytego.com/) — Alex Xu's system design course & newsletter
- [High Scalability](http://highscalability.com/) — real-world architecture case studies

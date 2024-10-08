# System Design

# Stages
## 1. [Plan](#plan)
  * Jira
  * Confluence
## 2. [Code](#code)
  * Spring Boot
  * React (..various other frameworks and libraries)
## 3. Build
  * Maven
  * Gradle
  * Nebula
## 4. Test
  * Chaos Monkey
## 5. Release
  * Jenkins
## 6. Deploy
  * Spinnaker
## 7. Operate
  * Pagerduty
## 8. Monitor
  * Splunk

## Architectural Patterns
- [x] Client-Server Architecture - https://www.redswitches.com/blog/client-server-architecture/
  * OS Types - https://www.redswitches.com/blog/types-of-operating-systems/
  * Web server - Nginx [https://youtu.be/JKxlsvZXG7c?si=1V9GIq3UAlNCVYaM , https://youtu.be/WuH0T9FHDZ4?si=QFFfM1nrU6zmaRuK]
- [x] Microservices Architecture: https://medium.com/hashmapinc/the-what-why-and-how-of-a-microservices-architecture-4179579423a9
- [ ] Serverless Architecture - https://www.datadoghq.com/knowledge-center/serverless-architecture/
- [ ] Event-Driven Architecture - https://www.confluent.io/learn/event-driven-architecture/
- [ ] Peer-to-Peer (P2P) Architecture - https://www.spiceworks.com/tech/networking/articles/what-is-peer-to-peer/
- [ ] Monolithic Architecture - 

## Key Concepts
- [ ] Scalability: https://lnkd.in/gpge_z76
- [ ] Latency vs Throughput: https://lnkd.in/g_amhAtN
- [ ] CAP Theorem: https://lnkd.in/g3hmVamx
- [ ] ACID Transactions: https://lnkd.in/gMe2JqaF
- [ ] Consistent Hashing: https://lnkd.in/gd3eAQKA
- [ ] Rate Limiting: https://lnkd.in/gWsTDR3m
- [ ] API Design: https://lnkd.in/ghYzrr8q
- [ ] Strong vs Eventual Consistency: https://lnkd.in/gJ-uXQXZ
- [ ] Synchronous vs. asynchronous communications: https://lnkd.in/g4EqcckR
  * Communication protocol default port: https://developer.mozilla.org/en-US/docs/Glossary/Port#
  * HTTP 1 vs HTTP 2 vs HTTP 3: https://youtu.be/a-sBfyiXysI?si=hV8s7tuwx-Hkvx4y
- [ ] REST vs RPC: https://lnkd.in/gN__zcAB
  * RPC - https://youtu.be/eRndYq8iTio?si=_g9q2liLVrLRn5Mk
  * gRPC - https://youtu.be/gnchfOojMk4?si=I2zqCAe9hN85WJsq
- [ ] Batch Processing vs Stream Processing: https://lnkd.in/gaAnP_fT
- [ ] Fault Tolerance: https://lnkd.in/dVJ6n3wA
- [ ] Consensus Algorithms: https://lnkd.in/ggc3tFbr
- [ ] Gossip Protocol: https://lnkd.in/gfPMtrJZ
- [ ] Service Discovery: https://lnkd.in/gjnrYkyF
- [ ] Disaster Recovery: https://lnkd.in/g8rnr3V3
- [ ] Distributed Tracing: https://lnkd.in/d6r5RdXG
- [ ] Top 15 Tradeoffs: https://lnkd.in/gnM8QC-z

## Building Blocks
- [ ] Horizontal vs Vertical Scaling: https://lnkd.in/gAH2e9du
  * https://www.redswitches.com/blog/horizontal-vs-vertical-scaling/
- [ ] Databases: https://lnkd.in/gti8gjpz
- [ ] Content Delivery Network (CDN): https://lnkd.in/gjJrEJeH
  * How CDN interacts with clients (or) how its configured? - Ist it on Web servers? - Dig deeper
- [ ] Domain Name System (DNS): https://lnkd.in/gkMcZW8V
  * How is DNS server setup? Do we have any popular providers?
  * How browsers talk to DNS? How they know which DNS to talk to?
- [ ] Caching: https://lnkd.in/gC9piQbJ
- [ ] Distributed Caching: https://lnkd.in/g7WKydNg
- [ ] Load Balancing: https://lnkd.in/gQaa8sXK
- [ ] SQL vs NoSQL: https://lnkd.in/g3WC_yxn
- [ ] Database Indexes: https://lnkd.in/dGnZiNmM
- [ ] HeartBeats: https://lnkd.in/gfb9-hpN
- [ ] Circuit Breaker: https://lnkd.in/gCxyFzKm
- [ ] Idempotency: https://lnkd.in/gPm6EtKJ
- [ ] Database Scaling: https://lnkd.in/gAXpSyWQ
- [ ] Data Replication: https://lnkd.in/gVAJxTpS
- [ ] Data Redundancy: https://lnkd.in/gNN7TF7n
- [ ] Database Sharding: https://lnkd.in/gMqqc6x9
- [ ] Failover: https://lnkd.in/dihZ-cEG
- [ ] Proxy Server: https://lnkd.in/gi8KnKS6
- [ ] Message Queues: https://lnkd.in/gTzY6uk8
- [ ] WebSockets: https://lnkd.in/g76Gv2KQ
- [ ] Bloom Filters: https://lnkd.in/dt4QbSUz
- [ ] API Gateway: https://lnkd.in/gnsJGJaM
- [ ] Distributed Locking: https://lnkd.in/gRxNJwWE
- [ ] Checksum: https://lnkd.in/ghNc5pfn

## Useful Resources
* https://github.com/ashishps1/awesome-system-design-resources?tab=readme-ov-file
* https://www.youtube.com/@ConceptandCoding/videos

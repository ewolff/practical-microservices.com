---
layout: default
title: "Microservices - A Pratical Guide - Klappentext"
description: "Microservices - A Pratical Guides: Content"
---

Content
---

Microservices have many advantages: Efficiently implementing more
features, bringing software into production faster, robustness and
easy scalability are among them. But implementing a microservices
architecture and selecting the necessary technologies are difficult
challenges.

This book shows microservices recipes that architects can customize
and combine into a microservices menu. In this way, the implementation
of microservices can be individually adapted to the requirements of
the project.

Eberhard Wolff introduces microservices, self-contained systems,
micro- and macro-architecture and the migration to microservices. The
second part shows the microservices recipes: Basic technologies such
as Docker or PaaS, frontend integration with links, JavaScript or ESI
(Edge Side Includes). This is followed by asynchronous microservices
with Apache Kafka or REST / Atom. In the synchronous approaches, the
book discusses REST with the Netflix stack, Consul, PaaS with Cloud
Foundry, and Kubernetes. Finally, operations is discussed: Log
Analysis with Elasticsearch and Kibana, Monitoring with Prometheus,
and tracing with Zipkin.

The second edition is based on the feedback about the first
edition. All chapters have been clarified, updated and extended. A new
chapter discusses services meshes, in particular Istio with an example
application. The second edition has about 35 pages more than the first
edition.

For each recipe there are suggestions for variations and
combinations. Readers can experience all technologies hands-on with a
demo project on GitHub. The outlook picks up on the operation of
microservices and also shows how the reader can start with
microservices in concrete terms.

## Table of Contents

* 0 Introduction
  * 0.1 Structure of the Book
  * 0.2 Target Group
  * 0.3 Prior Knowledge
  * 0.4 Quick Start
  * 0.5 Acknowledgements
  * 0.6 Website
  
#### Part I: Principles of Microservices Architecture
  
* 1 Microservices
  * 1.1 Microservices: Definition
  * 1.2 Reasons for Microservices
  * 1.3 Challenges
  * 1.4 Variations
  * 1.5 Conclusion

* 2 Micro and Macro Architecture
  * 2.1 Bounded Context and Strategic Design
  * 2.2 Technical Micro and Macro Architecture
  * 2.3 Operations: Micro or Macro Architecture?
  * 2.4 Give a Preference to Micro Architecture!
  * 2.5 Organizational Aspects
  * 2.6 Independent Systems Architecture Principles (ISA)
  * 2.7 Variations
  * 2.8 Conclusion

* 3 Migration
  * 3.1 Reasons for Migrating
  * 3.2 A Typical Migration Strategies
  * 3.3 Alternative Strategies
  * 3.4 Build, Operation, and Organization
  * 3.5 Variations
  * 3.6 Conclusion

### Part II: Technology Stacks

* 4 Docker Introduction
  * 4.1 Docker for Microservices: Reasons
  * 4.2 Docker Basics
  * 4.3 Docker Installation and Docker Commands
  * 4.4 Installing Docker Hosts with Docker Machine
  * 4.5 Dockerfiles
  * 4.6 Docker Compose
  * 4.7 Variations
  * 4.8 Conclusion

* 5 Technical Micro Architecture
  * 5.1 Requirements
  * 5.2 Reactive
  * 5.3 Spring Boot
  * 5.4 Go
  * 5.5 Variations
  * 5.6 Conclusion

* 6 Self-contained System (SCS)
  * 6.1 Reasons for the Term Self-contained Systems
  * 6.2 Definition
  * 6.3 An Example
  * 6.4 SCS and Microservices
  * 6.5 Benefits
  * 6.6 Challenges
  * 6.7 Variations
  * 6.8 Conclusion

* 7 Concept: Frontend Integration
  * 7.1 Frontend: Monolith or Modular?
  * 7.2 Options
  * 7.3 Resource-oriented Client Architecture (ROCA)
  * 7.4 Challenges
  * 7.5 Benefits
  * 7.6 Variations
  * 7.7 Conclusion
  
* 8 Recipe: Links and Client-side Integration
  * 8.1 Overview
  * 8.2 Example
  * 8.3 Variations
  * 8.4 Experiments
  * 8.5 Conclusion
  
* 9 Recipe: Server-side Integration using Edge Side Includes (ESI)
  * 9.1 ESI: Concepts
  * 9.2 Example
  * 9.3 Varnish
  * 9.4 Recipe Variations
  * 9.5 Experiments
  * 9.6 Conclusion
  
* 10 Concept: Asynchronous Microservices
  * 10.1 Definition
  * 10.2 Events
  * 10.3 Challenges
  * 10.4 Advantages
  * 10.5 Variations
  * 10.6 Conclusions
  
* 11 Recipe: Messaging and Kafka
  * 11.1 Message-oriented Middleware (MOM)
  * 11.2 The Architecture of Kafka
  * 11.3 Events with Kafka
  * 11.4 Example
  * 11.5 Recipe Variations
  * 11.6 Experiments
  * 11.7 Conclusion

* 12 Recipe: Asynchronous Communication with Atom and REST
  * 12.1 The Atom Format
  * 12.2 Example
  * 12.3 Recipe Variations
  * 12.4 Experiments
  * 12.5 Conclusion

* 13 Concept: Synchronous Microservices
  * 13.1 Definition
  * 13.2 Benefits
  * 13.3 Challenges  
  * 13.4 Variations
  * 13.5 Conclusion

* 14 Recipe: REST with the Netflix Stack
  * 14.1 Example
  * 14.2 Eureka: Service Discovery
  * 14.3 Router: Zuul
  * 14.4 Load Balancing: Ribbon
  * 14.5 Resilience: Hystrix
  * 14.6 Recipe Variations
  * 14.7 Experiments
  * 14.8 Conclusion 


* 15 Recipe: REST with Consul and Apache httpd
  * 15.1 Example
  * 15.2 Service Discovery: Consul
  * 15.3 Routing: Apache httpd
  * 15.4 Consul Template
  * 15.5 Consul and Spring Boot
  * 15.6 DNS and Registrator
  * 15.7 Recipe Variations
  * 15.8 Experiments
  * 15.9 Conclusion

* 16 Concept: Microservices Platforms
  * 16.1 Definition
  * 16.2 Variations
  * 16.3 Conclusion

* 17 Recipe: Docker Containers with Kubernettes
  * 17.1 Kubernetes
  * 17.2 The Example with Kubernetes
  * 17.3 The Example in Detail
  * 17.4  Additional Kubernetes Features
  * 17.5 Recipe Variations
  * 17.6 Experiments
  * 17.7 Conclusion

* 18 Recipe: PaaS with Cloud Foundry
  * 18.1 PaaS: Definition
  * 18.2 Cloud Foundry
  * 18.3 Example with Cloud Foundry
  * 18.4 Recipe Variations
  * 18.5 Experiments
  * 18.6 Serverless
  * 18.7 Conclusion

#### Part III: Operation

* 19 Concept: Operation
  * 19.1 Why Operation Is Important
  * 19.2 Approaches for the Operation of Microservices
  * 19.3 Effects of the Discussed Technologies
  * 19.4 Conclusion

* 20 Recipe: Monitoring with Prometheus
  * 20.1 Basics
  * 20.2 Metrics for Microservices
  * 20.3 Metrics with Prometheus
  * 20.4 Example with Prometheus
  * 20.5 Recipe Variations
  * 20.6 Experiments
  * 20.7 Conclusion

* 21 Recipe: Log Analysis with the Elastic Stack
  * 21.1 Basics
  * 21.2 Logging with the Elastic Stack
  * 21.3 Example
  * 21.4 Recipe Variations
  * 21.5 Experiments
  * 21.6 Conclusion

* 22 Recipe: Tracing with Zipkin
  * 22.1 Basics
  * 22.2 Tracing with Zipkin
  * 22.3 Example
  * 22.4 Recipe Variations
  * 22.5 Conclusion

* 23 Recipe: Service Mesh Istio
  * 23.1 What is a Service Mesh?
  * 23.2 Example
  * 23.3 How Istio Works
  * 23.4 Monitoring with Prometheus and Grafana
  * 23.5 Tracing with Jaeger
  * 23.6 Logging
  * 23.7 Resilience
  * 23.8 Challenges
  * 23.9 Benefits
  * 23.10 Variations
  * 23.11 Experiments
  * 23.12 Conclusion

* 24 And Now What?

* Appendix A: Installation of the Environment

* Appendix B: Maven Commands

* Appendix C: Docker and Docker Compose Commands

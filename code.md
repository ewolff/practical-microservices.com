---
layout: default
title: "Microservices - A Pratical Guide - Code"
description: "Microservices - A Pratical Guides: Code"
---

Code
---

The book contains a lot of code examples that explain specific
concepts. All projects are available on GitHub. The projects always
contain a `HOW-TO-RUN.md` file showing step-by-step instructions on
how the examples can be installed and started.  The examples are
independent of each other, so you can start with any one of them.

## Links and Client-side Integration (Chapter 8)


[Crimson Assurance](https://github.com/ewolff/crimson-assurance-demo)
is a example for a frontend integration with basic concepts like links
and JavaScript-based integration on the client. [How to
run](https://github.com/ewolff/crimson-insurance-demo/blob/master/HOW-TO-RUN.md)
explains how to run the example.

## Edge Side Includes (ESI) (Chapter 9)

The [ESI example](https://github.com/ewolff/SCS-ESI) shows how Edge Side
Includes (ESI) can be used to integrate the UI of microservices. On
microservice is written in Java with Spring Boot, the other one with
Go. The Go microservices is built using multi stage Docker containers.
[How to
run](https://github.com/ewolff/SCS-ESI/blob/master/HOW-TO-RUN.md)
gives a step by step guide how to run the example.

## Kafka (Chapter 11) 

The [Kafka example](https://github.com/ewolff/microservice-kafka) uses Kafka for
communication. Kafka is a message-oriented middleware and allows
systems to send messages to one another. [How to
run](https://github.com/ewolff/microservice-kafka/blob/master/HOW-TO-RUN.md)
contains all information to run the example.

## REST and Atom (Chapter 12)

This [example](https://github.com/ewolff/microservice-atom) uses REST
/ HTTP for asynchronous communication with the Atom format. The file
[How to
run](https://github.com/ewolff/microservice-atom/blob/master/HOW-TO-RUN.md)
explains how to run the example.

## Netflix Stack (Chapter 14)

The [Netflix example](https://github.com/ewolff/microservice) uses the
Netflix stack. The example is written in Java with Spring Cloud /
Boot. It uses Netflix Eureka for service discovery, Netflix Zuul for
routing, Hystrix for resilience and Ribbon for load balancing.  [How
to
run](https://github.com/ewolff/microservice/blob/master/HOW-TO-RUN.md)
shows how the example can be run.

## Consul and Apache httpd 	(Chapter 15)

The [Consul example](https://github.com/ewolff/microservice-consul) is
written in Java with Spring Cloud / Boot. The example uses Consul for
service discovery, Apache httpd for routing, Hystrix for resilience
and Ribbon for load balancing. [How to
run](https://github.com/ewolff/microservice-consul/blob/master/HOW-TO-RUN.md)
shows how the example can be run.

## Kubernetes (Chapter 17)

Kubernetes is a system to run Docker containers in a cluster. The
[Kubernetes example](https://github.com/ewolff/microservice-kubernetes)
is written in Java with Spring Cloud / Boot. It uses Kubernetes for
service discovery, routing and load balancing.  The example also uses
Hystrix for resilience. The code does not depend on Kubernetes.  [How
to
run](https://github.com/ewolff/microservice-kubernetes/blob/master/HOW-TO-RUN.md)
explains how to install Kubernetes and run the example.

## Cloud Foundry (Chapter 18)

Cloud Foundry is a PaaS. It provides an application with an
environment to run in. The [Cloud Foundry
example](https://github.com/ewolff/microservice-cloudfoundry) is written
in Java with Spring Cloud / Boot. Uses Cloud Foundry for deployment,
service discovery, routing and load balancing.  The example also uses
Hystrix for resilience. The code does not depend on Cloud Foundry.
[How to
run](https://github.com/ewolff/microservice-cloudfoundry/blob/master/HOW-TO-RUN.md)
explains in detail how to run the example.

##  Monitoring with Prometheus (Chapter 20)

The Consul example mentioned above also provides a [Prometheus
installation](https://github.com/ewolff/microservice-consul#prometheus)
for monitoring.

## Log Analysis with Elastic Stack (Chapter 21)

The Consul example mentioned above also contains an installation of
the 
[Elastic stack](https://github.com/ewolff/microservice-consul#elastic-stack)
for log analysis. 

## Tracing with Zipkin (Chapter 22)

[Zipkin](https://github.com/ewolff/microservice-consul#zipkin) can be
used to trace calls between microservices. It is also part of the
Consul example mentioned above.

## Service Mesh with Istio (Chapter 23)

The [Istio example](https://github.com/ewolff/microservice-istio)
extends the Atom example above to use the Istio service mesh. This
supports monitoring with Prometheus and Grafana, tracing with Jaeger,
Logging with Elasticsearch and Kibana, and also resilience with
retries, timeouts and circuit breaker. [How to
run](https://github.com/ewolff/microservice-istio/blob/master/HOW-TO-RUN.md)
explains how to run the example and install Istio on Kubernetes.



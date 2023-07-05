# currency-conversion-microservices

A group of microservices for converting currencies implemented in Spring Boot 3.

It consists of two microservices, currency-conversion-service and currency-exchange-service which talk with
each other to convert the currencies. The currency-conversion-service talks with currency-exchange services
to get the conversion rate from one currency to another currency. GKE is used as a naming server and as a
load balancer between the two microservices. Zipkin can be used to trace the incoming and outgoing requests
between the two microservices.

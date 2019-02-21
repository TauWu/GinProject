# Gin Project

Here is a project for a gin web-framework and more.

## Technology Stack

Type Name | Technology Tool Name | Remark 
--- | --- | --- 
Service Discovery | [Consul](https://github.com/hashicorp/consul) | - 
Service Deployment | [Docker](https://github.com/docker/docker-ce) + [Kubernetes](https://github.com/kubernetes/kubernetes) | - 
Serialize Data | Json + Protobuffer | Return json to Web Requests, and return protobuffer to micro-service. | - 
Communication Protocol | gRPC + HTTP | - 
Message Queue (MQ) | Kafka | Using [`sarama`](https://github.com/Shopify/sarama) to drive. 
WebFrameWork Base | Gin | - 
Redis Client | [RediGo](https://github.com/gomodule/redigo) | - 
Database Client | [sqlx](https://github.com/jmoiron/sqlx) | Native database operations are supported in Golang's base library. 

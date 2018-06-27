# microservice-architecture-quick-start
- C# 언어와 ASP.NET Core 환경을 이용하여 마이크로서비스 아키텍처를 구축하는 방법을 보여줍니다.
- (Demonstrates how to build a micro services architecture using the C # language and the ASP.NET Core environment.)


## Requirements

- Install [Docker](https://docs.docker.com/install/)
- Install [.NET Core 2.1](https://www.microsoft.com/net/download) 


## Limits
1. Used In-Memory Database


## Infrastructure

Orchestration
- [ ] Kubernetes
- [x] Docker
- [x] Docker-Compose

Infrastructure
- [ ] [Ocelot](https://github.com/ThreeMammals/Ocelot) (Api Gateway)
- [x] [NLog](https://github.com/NLog/NLog)
- [x] Swagger Integration ([Swashbuckle](https://github.com/domaindrivendev/Swashbuckle))
- [x] Entity Framework Core Code First
- [x] TraceId about Request
- [x] Guard
- [ ] [AutoMapper](http://automapper.org/)
- [x] Data Protection
- [x] [Polly](https://github.com/App-vNext/Polly)

Domain Driven Development
- [x] Aggregate Root
- [ ] ValueObject
- [x] CQRS
- [x] Event Sourcing
- [x] EventBus
- [ ] EventBus by RabbitMq
- [ ] Unit Of Work

Monitoring
- [x] Health Check
- [x] [App.Metrics](https://github.com/AppMetrics/AppMetrics) Integration
- [ ] [Grafana](https://www.datadoghq.com/ts/grafana-alternative)


## Run

#### Download Source Code

```
git clone https://github.com/powerumc/microservice-architecture-quick-start
```

#### Run Commands

##### 1. Move `provisioning` directory.

```
cd provisioning
```

##### 2. Run docker-compose

```
docker-compose up -d
```

## Tests

You can access via Postman for your tests. The document is generated by Postman.

https://documenter.getpostman.com/view/1730372/RWEiMe9X
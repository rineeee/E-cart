# E-cart

Commercial applications built with MSA.

## Architecture

Build msa using spring cloud.

<img width="477" alt="스크린샷 2022-12-17 오후 11 20 12" src="https://user-images.githubusercontent.com/62981406/208246471-ef4c5ce5-b9ad-41e2-b31b-d5840444fab8.png">


## Repository Link

### Micro Service
- [User](https://github.com/rineeee/User)
- [Order](https://github.com/rineeee/Order)
### API Gateway Service
### Discovery Service
### Config Service


## Detail

### Micro Service
- [User](https://github.com/rineeee/User)

[MSA PROJECT] E-cart의 유저 서비스
<img width="1098" alt="auth" src="https://github.com/rineeee/User/assets/62981406/d46ca883-92f2-4579-a3e4-f863fcef08bd">

- Discovery
  - Eureka Client
  
- Config
  - Spring Cloud Config
  - Spring Actuator
  - Spring Cloud Bus
  - rabbitmq

- Client
  - Open Feign
  - Resilience4j - Circuit Breaker

- Monitoring
  - Sleuth
  - Zipkin
  - Prometheus

- Auth
  - Spring Security

- DB
  - JPA
  - H2
 
- [Order](https://github.com/rineeee/Order)
  
[MSA PROJECT] E-cart의 주문 서비스
<img width="1602" alt="order" src="https://github.com/rineeee/Order/assets/62981406/74bc87ae-558b-4af3-879f-325ac10a465b">

- Discovery
  - Eureka Client
  
- MQ
  - Kafka

- Monitoring
  - Sleuth
  - Zipkin
  - Prometheus

- DB
  - MariaDB
### API Gateway Service
### Discovery Service
### Config Service

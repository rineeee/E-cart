# E-cart

Commercial applications built with MSA.

## Architecture

Build msa using spring cloud.

<img width="477" alt="스크린샷 2022-12-17 오후 11 20 12" src="https://user-images.githubusercontent.com/62981406/208246471-ef4c5ce5-b9ad-41e2-b31b-d5840444fab8.png">


## Repository Link

### Micro Service
- [User](https://github.com/rineeee/User)
- [Order](https://github.com/rineeee/Order)
- [Catalogs](https://github.com/rineeee/Catalogs)
### API Gateway Service
- [APIGateway](https://github.com/rineeee/APIGateway)
### Discovery Service
### Config Service
- [Config](https://github.com/rineeee/Config)


## Detail

### Micro Service
#### [User](https://github.com/rineeee/User)

[MSA PROJECT] E-cart의 유저 서비스
<img width="1098" alt="auth" src="https://github.com/rineeee/User/assets/62981406/d46ca883-92f2-4579-a3e4-f863fcef08bd">

- Discovery
  - Eureka Client
  
- Config
  - Spring Cloud Config
  - Spring Actuator
  - Spring Cloud Bus
  - Rabbitmq

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
 
#### [Order](https://github.com/rineeee/Order)
  
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

#### [Catalogs](https://github.com/rineeee/Catalogs)

[MSA PROJECT] E-cart의 카탈로그 서비스
<img width="1010" alt="catalogs" src="https://github.com/rineeee/Catalogs/assets/62981406/2cf8d494-a94d-41bb-bfc3-2b345b07abf1">

- Discovery
  - Eureka Client
  
- MQ
  - Kafka

- Monitoring
  - Sleuth
  - Zipkin
  - Prometheus

- DB
  - JPA
  - H2
### API Gateway Service
#### [APIGateway](https://github.com/rineeee/APIGateway)
[MSA PROJECT] E-cart의 API Gateway
<img width="1105" alt="api-gateway" src="https://github.com/rineeee/APIGateway/assets/62981406/21e26a60-b166-40c8-bd5f-45657e8a6f20">


- Discovery
  - Eureka Client

- Gateway
  - Spring Cloud Gateway
  
- Config
  - Spring Cloud Config
  - Spring Actuator
  - Spring Cloud Bus
  - Rabbitmq

- Monitoring
  - Prometheus
### Discovery Service
### Config Service
#### [Config](https://github.com/rineeee/Config)

[MSA PROJECT] E-cart의 config 관리

<img width="1010" alt="Config (2)" src="https://github.com/rineeee/E-cart/assets/62981406/2eac083a-61a4-4810-a633-362510dcdcd3">

- Config
  - Spring Cloud Config
  - Spring Actuator
  - Spring Cloud Bus
  - Rabbitmq

- Encryption
  - JDK Keytool(RSA)


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
### Discovery Service
### Config Service
#### [Config](https://github.com/rineeee/Config)

[MSA PROJECT] E-cart의 config 관리
<img width="437" alt="Config (1)" src="https://github.com/rineeee/Config/assets/62981406/578e207e-5fa1-4706-aff3-5bb7261c84e4">


- Config
  - Spring Cloud Config
  - Spring Actuator
  - Spring Cloud Bus
  - Rabbitmq

- Encryption
  - JDK Keytool(RSA)


# Config-Server
>Spring Cloud Config Server를 이용한 프로젝트입니다. 
<br>

## 목차
- [Dependency](#-dependency) <br>
- [Service Architecture](#-service-architecture)<br>
- [Config Server 흐름](#-config-server-flow)<br>

<br> 

## 🛠️ Dependency

|       기능       | 기술 스택                                           |
|:--------------:|:--------------------------------------------------|
|  Spring Boot   | - Spring Framework 2.7.14<br> - Java 17 <br> - Gradle 8.0 |
|  Spring Cloud  | - Config <br> - Eureka                            |
|  Monitoring    | - Actuator <br> - Spring Cloud Sleuth             |


<br>

## 🧩 Service Architecture

<img width="1618" alt="Architect (2) 복사본" src="https://github.com/wooriFisa-Final-Project-F4/.github/assets/109801772/27ac2b1d-8624-424f-aefb-4ceda4484b63">

## 🔄 Config Server 흐름
Spring Cloud MicroServices는 Spring Boot 프로젝트가 실행될 때, `config-server`를 이용하여 [깃허브 레포지토리](https://github.com/wooriFisa-Final-Project-F4/config-server-repository)에 있는 properties 파일들을 복호화 하여 읽어옵니다.
<br>  이렇게 properties를 집중 중앙식으로 관리하고, 암호화된 내용들을 업로드함으로서 중요한 설정 내용들을 손쉽게 수정하고 보호할 수 있습니다.


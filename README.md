# config-server

## Overview

Spring Cloud Config Server를 이용한 프로젝트입니다. 이 프로젝트는 다음과 같은 주요 기능 및 라이브러리를 활용하고 있습니다

- Eureka Client for service discovery
- Spring Cloud Config Server

## Requirements

- Java 17
- Spring Cloud Config

## Mechanism

### Project Architecture

<img width="1618" alt="Architect (2) 복사본" src="https://github.com/wooriFisa-Final-Project-F4/.github/assets/109801772/27ac2b1d-8624-424f-aefb-4ceda4484b63">

Spring Cloud MicroServices는 Spring Boot 프로젝트가 실행될 때, `config-server`를 이용하여 [깃허브 레포지토리](https://github.com/wooriFisa-Final-Project-F4/config-server-repository)에 있는 properties 파일들을 복호화 하여 읽어옵니다.
<br>  
이렇게 properties를 집중 중앙식으로 관리하고, 암호화된 내용들을 업로드함으로서 중요한 설정 내용들을 손쉽게 수정하고 보호할 수 있습니다.

## 참여자/기여자 목록

|                                                         김지운<br>PM(Project Manager)                                                         |
| :-------------------------------------------------------------------------------------------------------------------------------------------: |
| <img alt="김지운" src="https://github.com/Jimoou/Coding-Test/assets/109801772/6bb24ca5-a368-461a-9886-10fac02e7c20" height="100" width="100"> |
|                                                     [@Jimoou](https://github.com/Jimoou/)                                                     |
|                                               나비처럼 날아 벌처럼 쏘는 개발자가 되고 싶습니다.                                               |

---

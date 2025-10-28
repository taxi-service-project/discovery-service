# MSA 기반 Taxi 호출 플랫폼 - Discovery Service

Taxi 호출 플랫폼의 마이크로서비스들이 서로를 찾고 통신할 수 있도록 서비스 등록 및 검색 기능을 제공하는 **Eureka Server**입니다.

## 주요 기능

* 서비스 등록(Service Registration): 개별 마이크로서비스 인스턴스 정보 등록
* 서비스 검색(Service Discovery): 등록된 서비스 인스턴스 목록 제공
* 서비스 상태 확인(Health Checking): 등록된 서비스의 상태 모니터링

## 기술 스택 (Technology Stack)

* **Language & Framework:** Java, Spring Boot
* **Service Discovery:** Spring Cloud Netflix Eureka Server

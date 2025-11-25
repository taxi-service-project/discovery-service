# 🔎 Discovery Service (Eureka)

> **모든 마이크로서비스의 인스턴스 상태를 관리하고 검색(Service Discovery)하는 레지스트리 서버입니다.**

## 🛠 Tech Stack
| Category | Technology |
| :--- | :--- |
| **Language** | **Java 17** |
| **Framework** | Netflix Eureka Server |

## 🚀 Key Features
* **Dynamic Routing:** 각 서비스의 IP와 포트가 동적으로 변경되더라도, `Gateway`와 타 서비스가 **논리적인 서비스 이름(`lb://service-name`)**으로 통신할 수 있는 환경을 제공합니다.
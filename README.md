# paradase-ticket-server
- 사내 구내식당 식권 사용 및 월별, 사용자별 데이터 제공을 위한 서비스입니다.
## 개발 환경
- Java 1.8
- Gradle
- Spring Boot 2.7
- Spring Data JPA
- Spring Batch
- MariaDB 10.4
## 프로젝트 구조
### paradase-api
- 외부 HTTP 통신을 위한 모듈
### paradase-batch
- 월별, 사용자별 식대 사용 데이터 처리를 위한 모듈
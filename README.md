# 안녕하세요. _김승진_ 입니다.

[![](https://mazassumnida.wtf/api/mini/generate_badge?boj=ohksj77)](https://solved.ac/ohksj77/)
![](https://hits.sh/github.com/ohksj77.svg?view=today-total&color=58b8e7)

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"> <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">

## 💼 Career
- <strong>NEXON KOREA</strong> / Backend Engineer <sub>2025.09 ~ current</sub> <br> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white">

- <strong>EA Korea</strong> / <a href="https://blog.naver.com/eakblog/223614659714">Server Software Engineer 인턴</a> <sub>2025.01 ~ 2025.02</sub> <br> <img src="https://img.shields.io/badge/node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">

## 📬 Blog Posts
_* 단순 지식 전달의 글 보다는 주로 **개발하며 고민한 흔적** 위주로 블로그에 기록하고 있습니다._

| **Related Project** | **Blog Posts** |
|:----|:----|
|아이템 대량 개봉| 1. [API 서버 자체 부하분산 시스템 설계](https://ohksj77.tistory.com/274)|
| [이길저길](https://github.com/HongDam-org/TWTW) | 1. [실시간 시스템 설계](https://ohksj77.tistory.com/252) <br> 2. [실시간 통신 기술 성능 테스트](https://ohksj77.tistory.com/267) <br> 3. [알림 비동기 처리와 데드레터](https://ohksj77.tistory.com/260) <br> 4. [RateLimit 이슈와 캐시](https://ohksj77.tistory.com/261) <br> 5. [테스트 더블과 전략 패턴](https://ohksj77.tistory.com/263) <br> 6. [OpenAPI의 서킷브레이커 적용](https://ohksj77.tistory.com/262) <br> 7. [FullText 인덱스](https://ohksj77.tistory.com/259) |
| [showpot-core](https://github.com/AlreadyTakenSeat/showpot-core-BE) <br> [showpot-alarm](https://github.com/AlreadyTakenSeat/showpot-alarm-BE) | 1. [인프라 전환과 비용 절감](https://ohksj77.tistory.com/270) <br> 2. [커스텀 메트릭 수집과 모니터링](https://ohksj77.tistory.com/272) <br> 3. [조회수 동시성 이슈와 비동기 처리](https://ohksj77.tistory.com/271) |
| [GitRank v1](https://github.com/tukcom2023CD/DragonGuard-JinJin) <br> [GitRank v2](https://github.com/orgs/GitRank-v2/repositories?q=core-service+OR+open-api-worker+OR+alert-worker) | 1. [OpenAPI의 느린 응답과 스케줄링 기반 배치](https://ohksj77.tistory.com/258) <br> 2. [동시성 이슈와 Lock 전략 수립](https://ohksj77.tistory.com/251) <br> 3. [랭킹 시스템과 SortedSet](https://ohksj77.tistory.com/256) |
| 기타 탐구 작업 | 1. [UUID 및 Brin 인덱스 쿼리 개선](https://ohksj77.tistory.com/250) <br> 2. [알림 시스템 설계](https://ohksj77.tistory.com/268) <br> 3. [성능테스트 툴 비교](https://ohksj77.tistory.com/266) <br> 4. [Hibernate @SoftDelete 탐구](https://ohksj77.tistory.com/249) | 
| 오픈소스 직접 구현 | 1. [Kotlin으로 직접 MySQL 구현하기](https://ohksj77.tistory.com/276) <br> 2. [Kotlin으로 직접 Git 구현하기](https://ohksj77.tistory.com/277) <br> 3. [Kotlin으로 직접 API GW 구현하기](https://ohksj77.tistory.com/278) |

## 📂 Open Source
- **rabbitmq/rabbitmq-java-client** [PR#1469](https://github.com/rabbitmq/rabbitmq-java-client/pull/1469) [Release v5.23.0](https://github.com/rabbitmq/rabbitmq-java-client/releases/tag/v5.23.0)
  - 메시지의 requeue 메트릭 추가 및 해당 메트릭 수집 기능 추가
  - 메인테이너의 [PR#1476](https://github.com/rabbitmq/rabbitmq-java-client/pull/1476)에서 제 작업이 merge 되었습니다.

- **quartz-scheduler/quartz** [PR#1260](https://github.com/quartz-scheduler/quartz/pull/1260) [PR#1261](https://github.com/quartz-scheduler/quartz/pull/1261)
  - 다중 misfired trigger를 retrieve 중 예외 시 롤백 및 재처리로 인한 무한 실패 이슈를 에러 핸들링으로 해결

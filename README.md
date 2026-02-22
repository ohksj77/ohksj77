# 김승진 | Backend Engineer

- 제약이 많은 환경에서 **확장성과 복구 가능성**을 고려한 서버 구조를 설계해왔습니다.
- 기술적 근거뿐 아니라 **비즈니스 맥락**을 반영해 엔지니어링합니다.

Spring, MySQL, MongoDB, Redis, RabbitMQ, Docker

---
## Career Narrative

EA Korea 인턴
- 인프라 제약 속 **안정적인 100만 건 처리 구조**를 설계하며 대용량 처리 역량을 쌓았고, 운영 & 비즈니스의 중요성을 체감했습니다.

Nexon Korea
- 대용량·안정성 요구가 큰 도메인에서 강점을 확장하며, 운영 이슈를 통해 **우선순위 판단/비즈니스 기준**을 빠르게 학습하고 있습니다.
- 문제 해결 과정에서도 관측성·복구 가능성·운영 자동화 등 **운영에 도움이 되는 플랫폼 개선**을 지속하고 있습니다.

---

## Core Experience

### 레거시 프로시저 서버 로직으로 이전 (Nexon Korea)
- 평균 처리 시간 **3h 32m → 1m 13s (x174)**
- 단계별 트랜잭션 분리 + **실패 지점 추적/재시도** 가능한 복구 구조 설계
- 운영 리스크(실패/재처리) 제거

비즈니스를 위한 고민 과정: [ohksj77.tistory.com/283](https://ohksj77.tistory.com/283)

---

### 애플리케이션 레벨 부하 분산 설계 (EA Korea)
- “100만 건 부하를 줄이는 방법”이 아니라 **서버가 처리 여부를 자율 판단**하도록 문제 재정의
- 사내 첫 **RPC 기반 자율 판단 알고리즘/시스템** 설계 및 대용량 처리 구현
- **100만 건 9분 처리**, CPU **100% → 45%**, Memory **60% → 20%**

상세 설계와 기술적 탐구: [ohksj77.tistory.com/274](https://ohksj77.tistory.com/274)

---

## Open Source
rabbitmq-java-client / PR [#1469](https://github.com/rabbitmq/rabbitmq-java-client/pull/1469), Release [v5.23.0](https://github.com/rabbitmq/rabbitmq-java-client/releases/tag/v5.23.0)
  - requeue 메트릭 + 수집 API 추가로 재처리 상황 **관측 가능성 향상**
  - 기존 인터페이스 호환성 유지, 변경 범위 최소화

quartz-scheduler / PR [#1260](https://github.com/quartz-scheduler/quartz/pull/1260), [#1261](https://github.com/quartz-scheduler/quartz/pull/1261)
  - misfired trigger 예외 시 **무한 실패** 해결
  - 에러 핸들링 개선으로 롤백/재시도 **무한 루프 방지**

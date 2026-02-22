# 김승진 | Backend Engineer

- 제약이 많은 환경에서도 확장성과 복구 가능성을 고려한 서버 구조를 설계해왔습니다.
- 기술적인 근거 뿐만 아니라 비즈니스 맥락을 고려하며 엔지니어링합니다.

Tech Blog: [ohksj77.tistory.com](https://ohksj77.tistory.com)

Spring, MySQL, MongoDB, Redis, RabbitMQ, Docker

---

## Core Experience

### 레거시 프로시저 서버 로직으로 이전 (Nexon Korea)
- 3h 32m → 1m 13s (174배 개선)
- 단계별 트랜잭션 분리 및 복구 가능 구조 설계
- 실패 지점 추적 및 재시도 가능 설계, 운영 리스크 제거

비즈니스를 위한 고민 과정: [ohksj77.tistory.com/283](https://ohksj77.tistory.com/283)

---

### 애플리케이션 레벨 부하 분산 설계 (EA Korea)
- 100만 건 처리의 부하 해결 방안이 아닌 서버가 스스로 처리 여부를 판단 방법으로 문제 재정의
- 사내 첫 RPC 기반 자율 판단 알고리즘+시스템 설계, 대용량 데이터 처리 시스템 개발
- 100만 건 9분 처리
- CPU 100% → 45%, Memory 60% → 20%

상세 설계와 기술적 탐구: [ohksj77.tistory.com/274](https://ohksj77.tistory.com/274)

---

## Open Source
rabbitmq-java-client / PR [#1469](https://github.com/rabbitmq/rabbitmq-java-client/pull/1469), Release [v5.23.0](https://github.com/rabbitmq/rabbitmq-java-client/releases/tag/v5.23.0)
- requeue 메트릭 추가 및 메트릭 수집 API 구현, 메시지 재처리 상황 관측 가능성 향상
- 기존 인터페이스 호환성 유지, 함수형 스타일로 변경 범위 최소화
<br>

quartz-scheduler / PR [#1260](https://github.com/quartz-scheduler/quartz/pull/1260), [#1261](https://github.com/quartz-scheduler/quartz/pull/1261)
- misfired trigger 처리 중 예외 시 무한 실패 해결, 에러 핸들링 개선으로 롤백·재시도 무한 루프 방지

---

## Tech Blog 주요 카테고리
- [프로젝트-탐구](https://ohksj77.tistory.com/category/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%83%90%EA%B5%AC)
- [오픈소스-직접-구현](https://ohksj77.tistory.com/category/%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%EC%A7%81%EC%A0%91-%EA%B5%AC%ED%98%84)
- [개발-탐구](https://ohksj77.tistory.com/category/%EA%B0%9C%EB%B0%9C-%ED%83%90%EA%B5%AC)
- [커리어-회고](https://ohksj77.tistory.com/category/%EA%B8%B0%ED%83%80/%ED%9A%8C%EA%B3%A0)

# Node.js 백엔드 개발자를 위한 Jungle Boost 학습 가이드

이 가이드는 Node.js 기반 백엔드 개발자가 실무와 면접에서 요구되는 주요 지식과 스킬을 체계적으로 학습할 수 있도록 구성되어 있습니다.  
NestJS와 같은 최신 프레임워크 학습은 물론, 필수적으로 알고 있어야 할 CS 개념 및 아키텍처 이해도 함께 포함합니다.

---

## 1. Node.js 기본 이해
- Node.js의 특징과 동작 원리
- 이벤트 루프와 싱글 스레드
- Non-blocking I/O
- 런타임 vs 실행환경

## 2. JavaScript 비동기 처리
- 콜백과 콜백 헬
- Promise와 async/await
- 에러 핸들링 전략

## 3. Express.js 핵심 개념
- 라우팅과 미들웨어
- 에러 처리 미들웨어
- RESTful API 설계

## 4. NestJS 프레임워크
- 모듈(Module), 컨트롤러(Controller), 서비스(Service)
- 의존성 주입(Dependency Injection)
- 파이프(Pipe), 필터(Filter), 가드(Guard) 이해
- DTO와 유효성 검증 (class-validator)
- 인증/인가 (JWT, Passport)
- TypeORM/Prisma를 통한 DB 연동
- 환경별 설정 관리 및 ConfigModule

## 5. 데이터베이스
- 관계형 DB (PostgreSQL, MySQL 등)
- ORM vs Query Builder
- 모델링과 정규화
- 트랜잭션과 롤백
- Isolation Level
- N+1 문제와 해결 전략
- 인덱스 기본 개념과 실전 활용
- NoSQL DB (MongoDB 등)
- NoSQL과 RDB의 차이점
- Mongoose / Prisma를 통한 MongoDB 연동

## 6. 인증과 보안
- JWT와 세션의 차이
- 토큰 저장 위치(LocalStorage vs Cookie)
- 비밀번호 해시화(bcrypt)
- CORS, CSRF 기본 개념
- HTTPS, Helmet 등 보안 설정
- OAuth 2.0 개념 및 흐름 이해

## 7. 아키텍처 및 설계 원칙
- 의존성 주입(Dependency Injection) 원리 및 NestJS에서의 활용
- SOLID 원칙
- 계층형 아키텍처 (Controller → Service → Repository)
- 코드 구조와 폴더링 방식
- 마이크로서비스 vs 모놀리식 간단 비교

## 8. 테스트
- 유닛 테스트 vs 통합 테스트 vs E2E 테스트
- Jest, Supertest 기본 사용법
- Mocking과 DI를 활용한 테스트 전략
- 테스트를 위한 모듈 분리 전략

## 9. 운영과 배포
- 프로세스 매니저 (PM2)
- Docker 기초 및 NestJS 컨테이너화
- .env 설정과 환경 분리
- 로깅 시스템 (Winston, Morgan 등)
- CI/CD 흐름 기초 이해 (GitHub Actions 또는 GitLab CI)

## 10. 실무 필수 개념 모음
- HTTP와 HTTPS 차이
- HTTP 상태코드 정리
- REST API vs GraphQL
- API 문서화 (Swagger/OpenAPI)
- Git & GitHub 기본 협업 플로우
- Git Flow 전략과 코드 리뷰 문화

## 11. 참고 지식 (심화 및 면접 대비)
- Database Isolation Level 종류와 차이
- 트랜잭션 동시성 이슈와 해결 방식 (락, MVCC)
- 캐시와 Redis의 역할
- 스케줄링, 이벤트 기반 아키텍처
- CQRS, Event Sourcing 소개
- 도메인 주도 설계(DDD) 기본 개념

---

이 가이드는 Node.js 기반 백엔드 개발자로서 단순히 작동하는 서버를 만드는 단계를 넘어,  
**실무에서 유의미하게 쓰이는 개념과 구조를 이해하고 응용할 수 있는 수준**으로 성장하는 것을 목표로 합니다.

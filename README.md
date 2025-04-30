# 📌 StudyCafe_final 프로젝트

## 🛠 개발 환경
- **IDE**: IntelliJ
- **API 테스트 도구**: Postman
- **DB 툴**: MySQL Workbench
- **버전 관리**: GitHub

---

## 🔧 사용 기술 스택

### 백엔드
- Java 11
- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Spring AOP
- Interceptor, Filter
- @ExceptionHandler, @ControllerAdvice
- OAuth 2.0

### Build Tool
- Gradle 8

### Database
- MySQL
- H2

### 프론트엔드
- JavaScript
- Thymeleaf

---

## 🗂 주요 키워드
RESTful API, 시큐리티, JPA, 페이징, 트랜잭션, 예외처리, OAuth 2.0, 테스트, Git 버전관리, 클린코드

---

## ✅ 주요 구현 사항

### 🔁 기존 프로젝트 유지보수 및 기능 개선
- 레거시 코드 분석 및 구조 개선
- 중복 로직 제거 및 서비스/레포지토리 계층 분리 리팩토링
- 클린 코드 원칙 기반 리팩토링

### 📦 주문 기능 개발 (JPA 기반)
- JPA 기반 도메인 설계 및 CRUD 기능 최적화
- 주문 도메인 및 연관 관계(회원, 상품) 매핑
- 주문 생성 및 상태 변경 로직 구현
- 영속성 전이(Cascade) 및 지연 로딩(Lazy Loading) 전략 적용

### 🔐 인증 및 보안 기능 구현
- OAuth 2.0 기반 소셜 로그인 구현 (구글, 네이버 연동)
- 사용자 권한(Role)에 따른 Role-Based Access Control(RBAC) 시스템 구현
- Spring Security 기반 인증/인가 시스템 고도화
  - URL 패턴별 접근 권한 설정 (@PreAuthorize, SecurityConfig)
  - 인증 실패/인가 실패 핸들러 구현
- 인증 후 JWT 기반 세션 관리 구조 도입

### 🧪 테스트 및 품질 개선
- 서비스/도메인 단위의 단위 테스트(JUnit5) 작성
- RestController 테스트를 위한 MockMvc 활용
- 의존성 주입 및 테스트 가능한 구조로 개선

---

## 🧩 초기 통합 시스템 구현 (JSP 기반)
- 스터디카페 통합 서비스 웹사이트 기획 및 구현
- 스터디룸 예약, 상품 구매, 커뮤니티 기능 통합 제안 및 개발
- 상품 관리 기능 (등록/수정/삭제, 카테고리 관리)
- 커뮤니티 게시판 (글 작성, 수정, 댓글)
- Spring MVC 기반 웹 구조 구성
- Front-Controller 패턴 기반 DispatcherServlet 구성
- JSP 기반 뷰 렌더링 처리 및 Oracle DB 연동

# FreshBox – Android Client (Team Project)


바코드 기반 식재료 관리 및 레시피 추천 서비스입니다.  
Android 앱과 Spring Boot 백엔드가 REST API로 통신합니다.

---

## 👤 My Role (Backend)
- 회원가입 / 로그인 API 구현
- 바코드 스캔 결과를 외부 상품 API와 매칭
- 매칭된 식재료를 냉장고 메인 화면에 표시
- 레시피 자동 추천 API 연동 및 데이터 가공
- Controller / Service / Repository 구조로 백엔드 기능 분리
- 팀원과 협업하여 API 명세 공유 및 연동

---

## 🛠 Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- REST API

---

## ✨ Implemented APIs
- POST `/api/auth/register` : 회원가입
- POST `/api/auth/login` : 로그인
- GET `/api/ingredients` : 냉장고 식재료 조회
- POST `/api/ingredients` : 바코드 기반 식재료 등록
- GET `/api/recipes` : 보유 재료 기반 레시피 추천

---

## 🧠 What I Learned
- 요청 → Controller → Service → Repository → DB 흐름 이해
- 외부 API 응답 데이터를 서비스 요구사항에 맞게 가공하는 방법
- 협업 환경에서 역할 분리와 API 명세의 중요성

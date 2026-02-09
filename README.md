# FreshBox – Backend Contribution

## 프로젝트 개요
바코드 기반 식재료 관리와 레시피 추천을 제공하는 서비스입니다.
안드로이드 앱과 Spring Boot 서버가 REST API로 통신합니다.

## 👤 My Role (Backend)
- 회원가입 / 로그인 API 구현
- 바코드 스캔 결과를 외부 상품 API와 매칭
- 매칭된 식재료를 냉장고 메인 화면에 표시
- 레시피 추천 API 연동 및 데이터 가공

## 🔧 Tech Stack
- Java 17, Spring Boot
- JPA, MySQL
- REST API

## ✨ Implemented Features
- POST /api/auth/register
- POST /api/auth/login
- GET /api/ingredients
- POST /api/ingredients (barcode 기반)

## 🧠 What I Learned
- Controller / Service / Repository 역할 분리
- 외부 API 응답 처리 및 데이터 가공
- 협업 환경에서 API 명세 맞추기

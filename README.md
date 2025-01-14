# LotteOn 

![header](https://capsule-render.vercel.app/api?type=wave&color=gradient&height=250&section=header&text=🛒LotteOn%20Project🛒&fontSize=70&fontAlign=50)

<p align="center">
  <img src="./LotteERD.png" alt="ERD 다이어그램" width="300px">
</p>

## 📖 프로젝트 개요
LotteOn 프로젝트는 **롯데 e-커머스** 환경과 유사한 **쇼핑몰 플랫폼**을 개발하기 위해 설계되었습니다. 쇼핑몰의 기본적인 기능을 포함하며, 사용자 경험과 효율적인 백엔드 설계에 초점을 맞춘 웹 애플리케이션입니다.

---

## 🎯 프로젝트 목표
- **쇼핑몰의 필수 기능 구현**: 회원 관리, 상품 관리, 주문 및 장바구니, 리뷰 시스템 등
- **실제 환경에 가까운 설계 및 구현**: 데이터베이스 설계, 클라우드 환경 대응
- **사용자와 관리자 모두를 위한 플랫폼 개발**: 직관적인 UI/UX와 관리자 전용 기능 제공

---

## 🛠️ 기술 스택
### Backend
- **Java** / **Spring Boot** / **Spring Security**
- **JPA** / **MySQL**
- **Redis** (캐싱 및 성능 최적화)

### Frontend
- **HTML5** / **CSS3** / **JavaScript**
- **Thymeleaf**

### DevOps & Tools
- **AWS** (클라우드 배포)
- **GitHub** (버전 관리)
- **DBeaver** (DB 관리)

---

## 👩‍💻 팀원 소개

| 이름       | 주요 담당 기능                                            |
|------------|-----------------------------------------------------------|
| **황수빈(팀장)**   | - 프로젝트 및 일정 관리<br>- DB ERD 작성<br>- article (faq, qna, notice)<br>- point, coupon, review<br>- config (info, version)<br>- 사용자 행동패턴 분석 |
| **강은경**   | - 작업일지, 마일 스톤 등 문서작업<br>- user<br>- 소셜 SNS 로그인<br>- config (terms)<br>- cart |
| **강중원**   | - category<br>- banner, terms<br>- redis 캐싱처리<br>- 상품 검색, 목록<br>- 비동기식 처리 |
| **전규찬**   | - product<br>- product option<br>- product detail<br>- article (채용) |
| **조수빈**   | - order<br>- orderItems<br>- orderDelivery<br>- 전반적인 ERD 작업 및 DB 담당 |


---

## 📅 개발 일정
**2024년 10월 18일 ~ 2024년 11월 15일 (4주)**

1. **10월 3주차**: 프로젝트 기획 및 데이터베이스 설계
2. **10월 4주차**: 화면 설계 및 기본 개발 환경 구축
3. **11월 1주차**: 기능 구현
4. **11월 2주차**: 테스트 및 최종 배포

---

## 🏗️ 시스템 설계

### 아키텍처
- **3계층 구조**: Controller, Service, Repository
- **RESTful API** 설계
- **ERD**
<img src="./LotteERD.png" alt="ERD 다이어그램" width="500px">

### 주요 기능
#### 사용자
- 회원가입, 로그인/로그아웃
- 상품 목록 조회 및 검색
- 상품 상세보기 및 리뷰 작성
- 장바구니 및 주문 기능
- 쿠폰 다운로드 및 사용
- 고객센터 문의글 작성 및 확인 

#### 관리자
- 회원 관리 (활성/비활성화)
- 상품 수정, 삭제
- 주문 및 매출 관리
- 채용하기
- 포인트 관리
- 쿠폰 관리 (발급 및 이력)
- 고객센터
- 배송 관리

#### 판매자 
- 상품 등록, 수정, 삭제
- 주문 및 매출 관리
- 상품 관련 문의 답변
- 상점 관리
- 쿠폰 관리 (발급 및 이력)
- 배송 관리

---

## 🎥 기능 시연
[시연 영상 바로가기](https://www.youtube.com/watch?v=RJ5dJrYDLHg) 

---

## 🤝 질문 및 답변
프로젝트에 대한 문의는 아래 연락처로 부탁드립니다:
- **최준혁**: (mailto:loveu9911111@gmail.com)
- **GitHub Issues**: 프로젝트 관련 이슈나 버그는 [GitHub Issues](https://github.com/team1-lotteon/issues)에서 보고해주세요.

---

## 🌟 감사합니다!  
프로젝트를 방문해주셔서 감사합니다. 여러분의 피드백은 저희에게 큰 도움이 됩니다. 😊

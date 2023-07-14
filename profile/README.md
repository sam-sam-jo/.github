# 3355_헬스 멤버쉽 플랫폼
Client RP : https://github.com/sam-sam-jo/3355-frontend <br/>
Server RP : https://github.com/sam-sam-jo/3355-backend <br />

## 목차
- [1️⃣ 프로젝트 개요](#1️⃣프로젝트-개요)
- [2️⃣ 개발환경](#2️⃣개발환경)
- [3️⃣ 팀원소개](#3️⃣팀원소개)
- [4️⃣ 테이블구조](#4️⃣테이블구조)
- [5️⃣ 시스템 구조](#5️⃣시스템구조)
- [6️⃣ 프로그램 화면](#6️⃣프로그램화면)

# 1️⃣프로젝트-개요
- 헬스장 내부 멤버쉽 카드를 발급하여 다양한 혜택을 제공하는 플랫폼을 개발한다.
- 고객은 소셜 커뮤니티 활동, 출석 이벤트 등을 통해 멤버쉽 등급을 올릴 수 있다.
- 멤버쉽 카드를 이용한 온라인 및 오프라인 결제가 가능하고, 등급에 따라 일정 비율의 포인트가 적립된다.

# 2️⃣개발환경
- 사용언어: Java, Javascript, SQL
- 사용 툴: SpringBoot, React, Material UI
- 데이터베이스: Oracle, AWS S3 

# 3️⃣팀원소개

| 유지만(팀장) [Github](https://github.com/jiman-you) | 강태영 [Github](https://github.com/teon98) | 김경윤 [Github](https://github.com/KKangBro) | 이택주 [Github](https://github.com/Taek-ha) |
| :--- | :--- | :--- | :--- | 
|<img width="100" alt="taeyoung" src="https://avatars.githubusercontent.com/u/80306786"> | <img width="100" alt="eunbean" src="https://avatars.githubusercontent.com/u/49816869">| <img width="100" alt="soojeong" src="https://avatars.githubusercontent.com/u/19795060"> | <img width="100" alt="soojeong" src="https://avatars.githubusercontent.com/u/109137596"> |
| 계정관리 <br> 카드 커스텀 | UI/UX <br> 프론트 구조 설계 <br> 커뮤니티 | 바코드 결제 시스템 <br> 결제 및 포인트 내역 서비스 <br> 알림 서비스 | 바코드 생성 시스템 <br> 카드 서비스 <br> 알림 서비스


# 4️⃣테이블구조
![ERD 캡쳐](image.png)

# 5️⃣시스템구조
![서비스 흐름도](%EC%82%BC%EC%82%BC%EC%98%A4%EC%98%A4_%EB%B0%9C%ED%91%9C%EC%9A%A9_PPT-010.png)

# 6️⃣프로그램화면
### 1) 로그인, 충전 알림 화면
<video src="01_%EB%A1%9C%EA%B7%B8%EC%9D%B8,%EC%B6%A9%EC%A0%84%EC%95%8C%EB%A6%BC.mp4" controls title="Title" width="30%"></video>

### 2) 회원가입 화면
<video src="01_%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85.mp4" controls title="Title" width="30%"></video>
### 로그인, 충전 알림 화면

### 3) 결제
<video src="02_%EA%B2%B0%EC%A0%9C.mp4" controls title="Title" width="30%"></video>

### 4) 충전, 카드 내역
<video src="02_%EC%B6%A9%EC%A0%84,%20%EC%B9%B4%EB%93%9C%20%EB%82%B4%EC%97%AD.mp4" controls title="Title" width="30%"></video>

### 5) 결제, 알림 전체 읽기
<video src="03_%EA%B2%B0%EC%A0%9C,%20%EC%95%8C%EB%A6%BC%20%EC%A0%84%EC%B2%B4%20%EC%9D%BD%EA%B8%B0.mp4" controls title="Title" width="30%"></video>

### 6) 포인트 결제, 카드내역 필터링
<video src="03_%ED%8F%AC%EC%9D%B8%ED%8A%B8%EA%B2%B0%EC%A0%9C,%20%EC%B9%B4%EB%93%9C%EB%82%B4%EC%97%AD%20%ED%95%84%ED%84%B0%EB%A7%81.mp4" controls title="Title" width="30%"></video>

### 7) 마이페이지, 출석체크 포인트
<video src="04_%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80%20%EC%B6%9C%EC%84%9D%EC%B2%B4%ED%81%AC%20%ED%8F%AC%EC%9D%B8%ED%8A%B8.mp4" controls title="Title" width="30%"></video>

### 8) 마이페이지, 출석체크, 포인트 내역, 알림 전체 읽기
<video src="04_%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80,%20%EC%B6%9C%EC%84%9D%EC%B2%B4%ED%81%AC,%20%ED%8F%AC%EC%9D%B8%ED%8A%B8%EB%82%B4%EC%97%AD,%20%EC%95%8C%EB%A6%BC%20%EC%A0%84%EC%B2%B4%EC%9D%BD%EA%B8%B0.mp4" controls title="Title" width="30%"></video>

### 9) 카드커스텀 카드 뒤집기 기능
<video src="05_%EC%B9%B4%EB%93%9C%EC%BB%A4%EC%8A%A4%ED%85%80%20%EC%B9%B4%EB%93%9C%EB%92%A4%EC%A7%91%EA%B8%B0.mp4" controls title="Title" width="30%" ></video>

### 10) 비밀번호 찾기 기능
<img src="image-1.png" width="70%"/>

### 11) 커뮤니티 기능
<video src="%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%EA%B8%B0%EB%8A%A52%20(1).mp4" controls title="Title" width="40%" ></video>

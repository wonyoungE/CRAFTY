![header](https://capsule-render.vercel.app/api?type=blur&height=200&text=CRAFTY&animation=fadeIn&color=gradient&colorA=E0F2F7&colorB=D3BCDF&fontColor=444)
## 💫 누구나 판매하고 구매할 수 있는 펀딩 플랫폼, CRAFTY 🎁

개인 창작자들이 쉽게 펀딩을 열고, 후원자들을 모을 수 있는 있는 펀딩 플랫폼입니다.

## ✨ 주요 기능
### 펀딩(굿즈) 검색, 등록 및 관리자 승인

- (구매자) 카테고리, 진행 여부(진행중/진행예정/종료), 정렬(최신/인기) 기준으로 펀딩 프로젝트를 검색 및 필터링
- (판매자) 펀딩(굿즈) 프로젝트를 등록하고, 참여자 목록 및 결제 내역 확인
- (관리자) 등록된 펀딩을 심사하고 승인/거절 시 **JavaMailSender**로 판매자에게 알림 메일 발송

### 카카오페이 결제 연동

- **포트원(구 iamport) 결제 API**을 연동한 **카카오페이 API 결제** 기능
- 결제 완료 시 구매자에게 결제 내역 알림 메일 발송

### 배송 관리 및 실시간 조회

- (판매자) 주문 건에 대해 운송장 번호 등록
- (구매자) **스마트택배 API**와 연동하여 ‘참여 굿즈 확인’ 페이지에서 **실시간 배송 조회**하는 기능

### 회원 관리 및 이메일 알림

- 기본적인 회원가입/로그인 (중복 확인, ID/PW 찾기) 및 프로필 관리 기능
- ‘펀딩 오픈 알림’, ‘회원가입’, ‘결제 완료’ 등 이벤트 발생 시 **JavaMailSender**를 통해 사용자에게 알림 메일 발송

### 펀딩 상태 자동화 및 알림 메일 자동 발송 (Spring Scheduler)

- 매일 자정에 서버가 자동으로 동작하도록 **스케줄링** 기능 구현
- 오픈 예정인 펀딩을 진행중으로, 마감일이 지난 펀딩을 종료(성공/실패)로 **자동 업데이트**
- 알림 신청한 사용자들에게 **펀딩 오픈 알림 메일을 자동으로 발송**

## 🛠️ Stacks
<div>
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=SPRING&logoColor=white">
  <img src="https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=mybatis&logoColor=white">
<br>

  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
  <br>

  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
  <br>

  <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white">
  <br>
  
  <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white">
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> 
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
</div>

## 🗂️ 프로젝트 산출물

### 📆 WBS
  <img src="https://github.com/user-attachments/assets/519d1c78-7610-4883-aecc-1b1058b27372">

### 🗄️ERD
  <img src="https://github.com/user-attachments/assets/ec5ae240-7905-4a82-b7ad-04c66d296779">

### [🎨 Figma](https://www.figma.com/design/4HKEd5WUOKEaDFpcQyLftq/CRAFTY?node-id=0-1&t=8hA8Or8yzvC7uw7R-1)
  <img src="https://github.com/user-attachments/assets/9ac3e11a-2e35-4825-828f-fa98a7f04a1b">

## 🪄 서비스 화면
<h3>1. 메인 화면</h3>
<img width="1918" height="959" alt="image" src="https://github.com/user-attachments/assets/a383a3b2-4c20-4915-9b01-049bf7a5b293" />

<h3>2. 굿즈 상세 & 결제 화면</h3>
<img width="1917" height="958" alt="image" src="https://github.com/user-attachments/assets/4bff493e-a8d1-4e11-ba47-ff75da0bfcd6" />

<h3>3. 개인 프로필 화면</h3>
<img width="1812" height="906" alt="image" src="https://github.com/user-attachments/assets/d944991c-53c5-41be-9fde-179b37ae6e3c" />

<h3>4. 관리자 화면</h3>
<img width="1916" height="958" alt="image" src="https://github.com/user-attachments/assets/2e4300dd-d3d4-4073-a7ef-10458c48347a" />



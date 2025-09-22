---
layout: post
title: "shoppingMall"
subtitle: "MiniProject"
permalink: /blog/shoppingMall
---

<div style="margin:10px 0;">
  <a href="https://github.com/jrj1533/shoppingMall" target="_blank" class="btn btn-dark">GitHub</a>
  <a href="https://www.erdcloud.com/d/885HpyDu2DsreRWr8" target="_blank" class="btn btn-gray">ERD</a>
  <a href="https://docs.google.com/spreadsheets/d/1nq_2JE1Glr-NHnPQepheWDQer0huWSuSwJrtRJHRLis/edit?gid=458429680#gid=458429680" target="_blank" class="btn btn-info">WBS</a>
  <a href="https://docs.google.com/spreadsheets/d/1NVzBaICrkpvecXyAXfLW_jw8Wl_FaJOsl7uvMSYpYas/edit?gid=2120964424#gid=2120964424" target="_blank" class="btn btn-warning">요구사항정의서</a>
</div>

---

## 📅 2025.08.01 ~ 2025.09.10
방송국 내부 업무 효율화를 위한 그룹웨어 시스템  
캘린더, 예약, 근태, 게시판, 전자결재 등 방송국 업무를 통합 관리합니다.

---

## 📖 프로젝트 개요

### 개발 목적
방송국 내부 업무를 웹으로 통합 관리하여 효율화

### 주요 특징
- 캘린더, 예약, 근태, 게시판, 전자결재 등 필수 업무 통합  
- 역할 기반 기능 분리 (관리자 / 직원) 
- 직원들의 의사소통을 위한 채팅기능
- 일정, 예약 중복 방지, 결재 진행 상태 확인 등 업무 편의 기능 제공

---

## 👥 사용자 역할 및 기능

### 📌 관리자
- 회원 관리  
- 회의실, 편집실, 차량 예약 관리  
- 캘린더 일정 등록/수정/삭제  
- 게시판 관리 및 공지사항 등록  

### 👨‍💼 직원
- 개인 일정 확인 및 관리  
- 예약 신청 (회의실, 편집실, 차량)  
- 근태 등록 (출근, 퇴근, 외근)  
- 게시판 글 작성/수정/삭제  
- 결재 문서 확인 및 서명 제출
- 실시간 채팅 기능

---

### 🧑‍💻 기여자 정보
- 김성민 / 캘린더, 근태, 마이페이지 구성
- 김예진 / 결재, 방송편성 구성
- 장정수 / 예약, 게시판 구성  
- #### 장지영 / 로그인, 직원리스트, 채팅, 메인화면 구성

---

### 🙋 담당 기능
- #### 로그인 기능
  - Spring Security 사용
  - session으로 로그인 상태 유지
- #### 메인화면
  - 출퇴근, 휴가, 결재, 예약, 공지사항 등 레이아웃 구성 및 클릭 시 해당 페이지로 이동
  - 방송그룹웨어이므로 실시간 뉴스 영상 표시
  - 날씨api를 통해 날씨 기능 구현
  - 긴급공지사항 경우 하단에 애니메이션으로 표시
- #### 직원 관리 및 리스트
  - 부서 / 팀 선택 시 등록날짜 포함해서 자동 사원번호 생성
  - 초기 비밀번호 직원 생년월일 생성
  - 부서명, 팀, 이름으로 직원 정보 검색 및 조회
- #### 채팅
  - WebSocker을 이용하여 실시간 양방향 메시지 기능
  - 조직도리스트에서 직원 선택 후 채팅방 초대
  - 인원수에 따라 개인,그룹채팅방으로 초대
  - 개인채팅방 나가도 상대방은 메시지 유지
  - 나간사람한테 메시지 보내면 초대안해도 채팅방으로 초대
  - 그룹채팅방에서 인원수 및 직원정보 확인
  - 채팅메시지 실시간 알림 기능

  ---

## ⚙️ 기술 스택

| **구분**       | **기술**              |
| -------------  | --------------------- |
| **Language**   | Java 21               |
| **Backend**    | Spring Boot           |
| **Frontend**   | JSP, JSTL, EL, jQuery |
| **Database**   | MySQL                 |
| **ORM**        | JPA / MyBatis         |
| **Build Tool** | Maven                 |
| **Server**     | Embedded Tomcat       |
| **기타**        | Lombok 등             |

---

## 📝 화면설계서

<iframe src="https://drive.google.com/file/d/1wnuqzsuz-Srgg0F3ATzhJQ327UF5pzv3/preview"
        frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true">
</iframe>

---

## 🎤 발표PPT

<iframe src="https://drive.google.com/file/d/1NIXjdUJAwdP4z8FE_VifDaIZwn5kDVho/preview"
        frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true">
</iframe>

---

## 🎬 시연영상
<iframe src="https://drive.google.com/file/d/18Fea2qlCaUQ42ipuhO4cR2Zbb7ynFV4I/preview"
        frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true">
</iframe>
---
title: Spray Project
layout: post
categories: [portfolio]
image: /assets/img/20210705/main.PNG
description: "SPRAY 프로젝트"
---

SPRAY 프로젝트란?<br>
파운데이션, 아이라이너 등 코스메틱 화장품을 대상으로 하여 회원들간 투표를 통해 최고의 제품을 선정하여 공유하는 커뮤니티 사이트 이다. 순위는 일주일간 유지되며 주초에 투표를 재개한다.

로그인 화면
<img src="/showRoom/assets/img/20210705/login.PNG"> 
로그인 폼 화면 이다. 휴대폰 번호를 입력하여 로그인이 가능하며, 로그인 시도시 회원 조건 여부 확인후 Spring Security 를 이용하여 사용자의 인증 및 권한 부여 과정을 거친뒤 토큰부여 처리를 하였다. 

회원가입 화면
<img src="/showRoom/assets/img/20210705/join.PNG"> 
회원가입 요청시 휴대폰 번호의 무결성 검증을 거친뒤 회원 가입 처리를 한다.

메인 화면
<img src="/showRoom/assets/img/20210705/main.PNG"> 
로그인 후 보여지는 첫 메인 화면이다. 각 게시판 별로 득표수가 가장 많을 품목을 10위 까지 노출하며 득표수와 투표 현황을 한눈에 볼 수 있다.
각 섹션별 하단 "show chart" 를 클릭시 투표 현황을 원형 그래프로 확인 할 수 있다. 

차트 현황
<img src="/showRoom/assets/img/20210705/chart.PNG"> 
차트위에 마우스 오버시 해당 파이의 화장품 품명과 득표수를 확인 할 수 있다.

게시글 목록
<img src="/showRoom/assets/img/20210705/boardlist.PNG"> 
메인화면내 게시글 클릭시 보여지는 게시판 목록이다. 

게시글 내용1
<img src="/showRoom/assets/img/20210705/content1.PNG"> 

게시글 내용2
<img src="/showRoom/assets/img/20210705/content2.PNG"> 
게시글 하단 엄지버튼을 클릭시 해당 게시글의 품목과 맵핑돼 있는 특표수의 카운트가 올라간다. 한번 추천한 품목은 중복으로 추천할 수 없다. 
추천여부는 해당 게시글의 버튼 색상이 베이지 색상 인지 여부로 판단할 수 있다.

게시글 작성
<img src="/showRoom/assets/img/20210705/boardWrite.PNG"> 
게시글 작성 포멧이다. 
Product 필드에 화장품명을 입력하면 자동 완성 목록이 드롭다운 되어 해당 품목과 맵핑되는 화장품 사진을 노출시킨다. 
<br>
<br>
사용 기술<br>

Java
iBatis
HTML
CSS3
javascript
Vue.js
<br>
<br>
DB<br>
MySQL
<br>
<br>
Framework<br>
Spring Boot
<br>
<br>
template 
mustache<br>
<br>
<br>
작업 후 느낀 점<br>
SPRAY 토이프로젝트의 진행 목적은 javascript와 Vue.js 기술에 대한 스터디가 목적이었다. 그러다보니 게시글 작성시 품목 필터링 처리와 HTML 을 통해 보여지는 템플릿 뷰 들을 컴포넌트로 구현하는데 있어 많은 시간이 걸렸다. 하지만 해당 프로젝트를 구현하면서 모르는 부분들을 퍼즐 조각 맞춰나가듯이 하나씩 알아갈수록 Vue 의 컴포넌트 기반 기술에 대한 편리함을 조금은 알거같았다. 앞으로도 프론트단을 구현할 때는 Vue.js 를 사용하게 되지 않을까 싶다. 


 

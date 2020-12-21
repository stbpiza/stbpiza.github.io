---
layout: post
title: Pokewith
feature-img: "assets/img/portfolio/cake.png"
img: "assets/img/portfolio/cake.png"
date: 31 August 2020
tags: [Portfolio, 팀프로젝트, Spring, Thymeleaf, MySQL, Vanilla JS]
---

팀프로젝트(프론트2, 백2)   

Spring, Thymeleaf, MySQL, Vanilla JS

포켓몬고 라는 게임을 함께 할 사람을 찾는 웹사이트   

facebook 소셜로그인 구현(https 구현)   
웹소켓 기반 채팅시스템 구현   
게시글 작성자가 댓글 채택시, 채택 대생자들과의 채팅방 생성   

<a href="https://github.com/stbpiza/pokewithBack">https://github.com/stbpiza/pokewithBack</a>   

## 개발방법

Spring 환경 세팅은 xml이 아닌 어노테이션 방식으로 구성하였습니다.   
   
기능 설계 -> 스토리 백로그 작성 -> 스프린트 백로그 작성 -> 본 프로젝트 개발 과정을 통해 진행하였습니다.   
   
api 명세서를 작성해 프론트와 서버의 통신을 원활하게 하였습니다.   

## 기여한 부분

프로젝트 아이디어 및 전반적인 설계를 담당하였습니다.   

facebook 소셜로그인을 구현하였고, facebook의 경우 https 사용이 필수이기에,   
SSH를 임시로 만들어서 https를 구현했습니다.   

DB설계를 하고 api 명세서 작성 및 mybatis를 통해 쿼리를 작성하였습니다.   

MVC 패턴을 통해 전반적인 뼈대를 만들었습니다. 

View를 Thymeleaf로 띄워서 그 위에서 javaScript가 돌아가도록 하였습니다.

## 어려웠던 부분

처음 프로젝트 계획할 때 실제로 배포하여 운영까지 하려고 했었습니다.   
그래서 기능들을 실제 사용할 수 있게끔 설계하였더니 구현하기가 어려웠습니다.   

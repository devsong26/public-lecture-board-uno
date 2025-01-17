# 게시판 서비스

[![GitKraken shield](https://img.shields.io/badge/GitKraken-Legendary%20Git%20Tools-teal?style=plastic&logo=gitkraken)](http://gitkraken.link/uno)

가장 기본적이고 보편적인 게시판 기능을 둘러볼 수 있는 서비스입니다. 2022년 6월 기준 가장 최신의 스프링 부트와 관련 기술들, 자바 17 기능들, 개발 도구들을 경험할 수 있도록 만들어졌습니다. [어드민 프로젝트](https://github.com/djkeh/fastcampus-project-board-admin)의 개발과 기능 사용은 이 프로젝트와 연관이 있습니다.

이 서비스는 [패스트캠퍼스](https://fastcampus.co.kr/)의 다음 강의용 프로젝트로 사용되었습니다.

* [10개 프로젝트로 시작하는 백엔드 웹개발 : 신입 개발자 취업 집중반 (w. Java/Spring Boot)](https://fastcampus.co.kr/dev_online_javaspring)
* [10개 프로젝트로 완성하는 백엔드 웹개발(Java/Spring)](https://fastcampus.co.kr/dev_online_befinal)

## 개발 환경

* Intellij IDEA Ultimate
* Java 17
* Gradle 7.4.1
* Spring Boot 2.7.0

## 기술 세부 스택

Spring Boot

* Spring Boot Actuator
* Spring Web
* Spring Data JPA
* Rest Repositories
* Rest Repositories HAL Explorer
* Thymeleaf
* Spring Security
* H2 Database
* MySQL Driver
* Lombok
* Spring Boot DevTools
* Spring Configuration Processor

그 외

* QueryDSL 5.0.0
* Bootstrap 5.2.0-Beta1
* Heroku

## 강의 찾아가기

게시판 서비스는 강의와 공부 목적으로 만들어진 프로젝트입니다.
따라서 강의의 어떤 시점으로든 코드를 찾아가서 쉽게 관찰할 수 있도록 되어 있습니다.
특정 강의 시점의 소스코드를 좀 더 편리하게 확인하고 싶다면 릴리즈 탭을 확인해 보세요.

* https://github.com/djkeh/fastcampus-project-board/releases

## 질문, 건의

프로젝트에 관해 궁금하신 점이나 건의 사항이 있으시다면 아래 항목을 이용해 주세요.

* 질문
    * 10개 프로젝트로 시작하는 백엔드 웹개발: https://fastcampus.co.kr/qna/234959/1
    * 10개 프로젝트로 완성하는 백엔드 웹개발: https://fastcampus.co.kr/qna/211368/1
* 버그 리포트, 제안 사항: https://github.com/djkeh/fastcampus-project-board/issues

## Reference

* 유즈케이스 다이어그램: [#4](https://github.com/djkeh/fastcampus-project-board/issues/4), https://viewer.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fdjkeh%2Ffastcampus-project-board%2Fmain%2Fdocument%2Fuse-case.svg
* API Endpoint 구글 시트: [#1](https://github.com/djkeh/fastcampus-project-board/issues/1), https://docs.google.com/spreadsheets/d/1S2FW7_LlePGF95strSYFJEsEQKoyZ9nGHWM8wZgFmSU/edit?usp=sharing
* 어드민 서비스: https://github.com/djkeh/fastcampus-project-board-admin

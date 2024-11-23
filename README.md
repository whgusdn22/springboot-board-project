# springboot-board-project

# 간단한 Spring Boot 게시판 프로젝트

이 프로젝트는 Spring Boot를 사용하여 만든 기본적인 게시판 애플리케이션입니다. YouTube 튜토리얼을 따라 간단한 CRUD 게시판을 처음부터 만들어보는 방식으로 진행되었습니다. 이 프로젝트의 목표는 Spring Boot의 기초를 배우고 이를 통해 기능적인 게시판을 만드는 것입니다.

## 기능

- 게시글 생성, 읽기, 수정, 삭제 (CRUD)

## 파일 첨부 기능

- 기본적인 페이지네이션 및 키워드 기반 게시글 검색

## 사용 기술

- Spring Boot

- Thymeleaf (HTML 템플릿 엔진)

- Spring Data JPA (데이터베이스 접근)

- Mirana DB (데이터베이스 관리)

- Bootstrap (간단한 스타일링)

## 엔드포인트

/board/list: 모든 게시글 보기

/board/write: 새 게시글 작성

/board/view?id={id}: 특정 게시글 보기

/board/modify/{id}: 기존 게시글 수정

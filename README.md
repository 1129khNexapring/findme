# FindMe
- 지하철 온라인 분실물 센터
- 프로젝트 참여자 / 권진실(팀장), 김선교(부팀장), 김아름, 이수연, 장민수, 전장영 
<br>

## 목차
###[1. 프로젝트 개요](##-프로젝트-개요)
###[2. 설계의 주안점](##-설계의-주안점 )
###[3. 사용기술 및 개발환경](##-사용기술-및-개발환경)
###[4. 프로젝트 기능 구현](##-프로젝트-기능-구현)
###[5. 주요기능](##-주요기능)
###[6. Document](##-Document)
<br>

## 프로젝트 개요
- 지하철 분실물과 같은 특수한 장소에 최적화된 보다 편리한 검색기능 제공
- 기존 타사이트에서 제공하는 분실물 찾기, 습득물 신고 기능 외 습득물택배서비스, 경매, 마일리지 서비스 등
사이트를 활성화 시키고 습득물 신고를 독려하는 서비스 제공 
- 분실물센터 + 경매 기능을 결합하여 모든 사용자(분실물 센터, 습득자, 분실자, 경매이용자)의 편익을 극대화하고자 함
<br>

## 설계의 주안점
- UI와 기능 모두 직관적인 사이트를 제작하여 사용자 경험을 극대화하고자 함. 
- AJAX 비동기 통신으로 사이트 이용 체감 속도 향상
<br>

## 사용기술 및 개발환경
|   |   |
|---|---|
|Server|Apache Tomcat|
|Coding Tool|Eclipse, VS CODE|
|언어|HTML, CSS, JavaScript, jQuery, JAVA|
|Database|Oracle|


![tools](https://user-images.githubusercontent.com/40844404/157788090-eb8c89c0-e109-4951-8ede-cb5afc0877ef.jpg)
<br>

## 프로젝트 기능 구현

### 권진실
+ 공통레이아웃
  - 프론트 페이지 구성
  - 습득물/분실물/경매 상세 AJAX조회
  - 현재페이지 하이라이팅
+ 경매 페이지
  - 좋아요 기능
  - 경매물품페이지(등록/삭제)
  - 경매 타이머세팅
  - 낙찰자 결제 기능

### 김선교
+ Found(습득물) 페이지
  - 습득물 신고 처리
  - 습득물 게시판
    * 게시물 내용 수정
    * 게시물 택배서비스 신청
    * 게시물 단일&복합 조건 검색
+ 공통 페이징 처리

### 김아름
+ 회원 기능 전반
  - 로그인
  - 로그아웃
  - 회원가입
  - 회원 탈퇴
  - 회원 정보 수정
  - 아이디 찾기
  - 비밀번호 찾기

### 이수연
+ 경매 페이지
  - 경매 리스트 목록
  - 제품종류,습득날자,현재최고입찰가 조회
+ 관리자페이지
  - 경매리스트 상태 수정
+ 마이페이지 
  - 경매 참여 이력

### 장민수
+ 마이페이지
  - 습득물 신고 이력
  - 분실물 신고 이력
  - 마일리지 적립 내역
  - 마일리지 사용 내역
  - 택배 서비스 신청 내역

### 전장영
+ lost(분실물) 페이지
  - 분실물 조회
  - 분실물 검색
+ found(습득물) 
  - 해시태그 추출, 워드클라우드 생성


## 주요기능
**분실물**
+ 분실물 신고
+ 분실물 검색

**습득물**
+ 습득물 등록
+ 급득물 수정

**회원관리**
+ 회원가입
+ 정보수정
+ 탈퇴

**습득물 경매**
+ 습득물 경매 입찰
+ 습득물 낙찰

**마일리지**
+ 마일리지 적립
+ 마일리지 사용

**택배**
+ 택배 신청
+ 택배 조회
<br>

## Document
작성중

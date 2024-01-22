# Stomaw

<br />

## 목차

- [Stomaw](#stomaw)
  - [목차](#목차)
  - [프로젝트 소개](#프로젝트-소개)
    - [프로젝트 배경](#프로젝트-배경)
  - [페이지 및 기능](#페이지-및-기능)
  - [반응형 페이지](#반응형-페이지)
  - [해결한 문제들](#해결한-문제들)
  - [요구사항 정리](#요구사항-정리)
  - [라우터 설정](#라우터-설정)
  - [페이지 설계](#페이지-설계)
  - [컴포넌트 설계](#컴포넌트-설계)
    - [Header 컴포넌트](#header-컴포넌트)
    - [SideBar 컴포넌트](#sidebar-컴포넌트)
    - [HeaderTitle 컴포넌트](#headertitle-컴포넌트)
    - [StockPriceChart 컴포넌트](#stockpricechart-컴포넌트)
  - [고민](#고민)
  - [배운 것들](#배운-것들)
  - [사용된 기술](#사용된-기술)
  - [디렉토리 구조](#디렉토리-구조)
  - [커밋 컨벤션](#커밋-컨벤션)

<br />

## 프로젝트 소개

Stomaw은 증권 정보를 제공하여 회사를 발굴할 때 도움을 주는 증권 정보 제공 웹 사이트입니다.

<br />

### 프로젝트 배경

Stomaw은 기업 정보 및 주가, IPO 일정, 뉴스 등의 유용한 정보들을 간단하고 편리하게 확인할 수 있도록 개발하자는 생각과 더불어 Next JS, Tailwind CSS, Zustand와 같은 기술들과 새롭게 관심을 가지게 된 SEO, 애드센스를 간단하고 빠르게 적용시켜보고자 하는 생각에서 시작되었습니다.

<br />

## 페이지 및 기능

<br />

## 반응형 페이지

<br />

## 해결한 문제들

<br />

## 요구사항 정리

| 홈 페이지                                                                                                                       | 관심 종목 페이지                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="홈 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/8dc884ff-e423-4b23-9391-d566d6f4ff8e"> | <img width="700" alt="관심 종목 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/d5a1a834-c624-4580-9837-555eef5b417a"> |

| 상세 종목 페이지                                                                                                                       | IPO 일정 페이지                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="상세 종목 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/5eb7c402-511f-4b19-acec-0511f8820c06"> | <img width="700" alt="IPO 일정 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/8a95af61-12ee-4044-a511-81d02c7f2b13"> |

| 검색 페이지                                                                                                                       | 고객 지원 페이지                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="검색 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/9d7dfac8-6d58-46b9-9a37-3ba34f032a35"> | <img width="700" alt="고객 지원 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/fe60e44f-e42d-4a48-af59-3da4128e478a"> |

| 기타                                                                                                                              |
| --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="50%" alt="기타 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/1ef69306-4ed5-4667-9238-8d6c8201528a"> |

<br />

## 라우터 설정

| 경로              | 설명           |
| ----------------- | -------------- |
| /                 | 홈             |
| /company/interest | 관심 종목      |
| /company/ipo      | IPO            |
| /company/detail   | 기업 상세 정보 |
| /search           | 검색           |
| /settings         | 설정           |
| /login            | 로그인         |

<br />

## 페이지 설계

<br />

## 컴포넌트 설계

### Header 컴포넌트

| 디자인                                                                                                                                       | 구성                                                                                                                                       | 기능                                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| <img width="700" alt="Header 컴포넌트 디자인" src="https://github.com/devkmins/Stomaw/assets/59950909/f4fca0dc-a6d2-47c1-b7f0-1918f75fa690"> | <img width="700" alt="Header 컴포넌트 구성" src="https://github.com/devkmins/Stomaw/assets/59950909/cb5397ae-b9fd-4f37-b62a-c14b7d416176"> | <img width="700" alt="Header 컴포넌트 기능" src="https://github.com/devkmins/Stomaw/assets/59950909/27e9bb68-f8bb-4db2-9612-08b53596bbd6"> |

<br />

### SideBar 컴포넌트

| 디자인                                                                                                                                       | 구성                                                                                                                                                                                                                                                                               | 기능                                                                                                                                                                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="1100" alt="SideBar 컴포넌트 디자인" src="https://github.com/devkmins/Fico/assets/59950909/89b03761-42b2-482c-843d-e3696644e2f5"> | <img width="600" alt="SideBar 컴포넌트 구성" src="https://github.com/devkmins/Fico/assets/59950909/e4ee271b-eeaf-46fb-8f81-876192dfe96e"><img width="600" alt="SideBar 컴포넌트 구성" src="https://github.com/devkmins/Fico/assets/59950909/fc0403ea-6614-4061-968c-ec3862ad3fd6"> | <img width="600" alt="SideBar 컴포넌트 기능" src="https://github.com/devkmins/Fico/assets/59950909/4aa19df6-2065-4666-95c2-af594bb18624"><img width="600" alt="SideBar 컴포넌트 기능" src="https://github.com/devkmins/Fico/assets/59950909/6e5dac40-b8c4-4370-b12a-5a3d085f0c18"> |

<br />

### HeaderTitle 컴포넌트

| 디자인                                                                                                                                          | 구성                                                                                                                                          | 기능                                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="HeaderTitle 컴포넌트 디자인" src="https://github.com/devkmins/Fico/assets/59950909/c1e01a94-aacf-4691-bac6-3fd37c2fd6a0"> | <img width="700" alt="HeaderTitle 컴포넌트 구성" src="https://github.com/devkmins/Fico/assets/59950909/87374e96-91a7-4836-8d2d-5127cebcceaf"> | <img width="700" alt="HeaderTitle 컴포넌트 기능" src="https://github.com/devkmins/Fico/assets/59950909/618a288b-d3ee-4ad3-b96e-ce7c541c4a92"> |

<br />

### StockPriceChart 컴포넌트

| 디자인                                                                                                                                              | 구성                                                                                                                                              | 기능                                                                                                                                              |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="StockPriceChart 컴포넌트 디자인" src="https://github.com/devkmins/Fico/assets/59950909/f1c62fdf-8fa0-43f5-af1b-82beabd9274a"> | <img width="700" alt="StockPriceChart 컴포넌트 구성" src="https://github.com/devkmins/Fico/assets/59950909/da2f4e47-eadf-4c32-9b13-9efaccb32638"> | <img width="700" alt="StockPriceChart 컴포넌트 기능" src="https://github.com/devkmins/Fico/assets/59950909/503f5c55-6744-428b-93a6-0b51da87b530"> |

<br />

## 고민

<br />

## 배운 것들

<br />

## 사용된 기술

<br />

## 디렉토리 구조

<br />

## 커밋 컨벤션

| 제목     | 설명                                              |
| -------- | ------------------------------------------------- |
| feat     | 새로운 기능 추가                                  |
| fix      | 버그 수정                                         |
| refactor | 리팩토링                                          |
| design   | CSS 등 사용자 UI 디자인                           |
| init     | 프로젝트 초기 생성                                |
| remove   | 코드 제거 및 파일을 삭제하는 작업을 수행하는 경우 |
| edit     | 기존의 파일, 코드 수정 및 개선                    |
| types    | 공통 타입 추가                                    |
| README   | 리드미 작성                                       |

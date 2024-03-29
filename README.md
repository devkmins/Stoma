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

Stoma는 증권 정보를 제공하여 회사를 발굴할 때 도움을 주는 증권 정보 제공 웹 사이트입니다.

<br />

### 프로젝트 배경

Stoma는 기업 정보 및 주가, IPO 일정, 뉴스 등의 유용한 정보들을 간단하고 편리하게 확인할 수 있도록 개발하자는 생각과 더불어 Next JS, Tailwind CSS, Zustand와 같은 기술들과 새롭게 관심을 가지게 된 SEO, 애드센스를 간단하고 빠르게 적용시켜보고자 하는 생각에서 시작되었습니다.

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
| <img width="700" alt="홈 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/ec821087-6af4-48a7-a5d5-72825047d8d5"> | <img width="700" alt="관심 종목 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/670a3ee7-08a5-4a2c-bf82-0e6d96058e0d"> |

| 상세 종목 페이지                                                                                                                       | 뉴스 페이지                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="상세 종목 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/5eb7c402-511f-4b19-acec-0511f8820c06"> | <img width="700" alt="뉴스 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/9578f1b3-1355-45f3-aaf6-c5424a0db6b0"> |

| IPO 일정 페이지                                                                                                                       | 검색 페이지                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="IPO 일정 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/23c9cbd4-dd1f-42c7-b3d2-19552dc94aef"> | <img width="700" alt="검색 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/9d7dfac8-6d58-46b9-9a37-3ba34f032a35"> |

| 고객 지원 페이지                                                                                                                       | 기타                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| <img width="715" alt="고객 지원 페이지" src="https://github.com/devkmins/Stomaw/assets/59950909/507a9389-4e66-4963-b26e-a3646f964684"> | <img width="700" alt="기타" src="https://github.com/devkmins/Stomaw/assets/59950909/dd32e5dc-51cc-4e75-b8aa-3f2a82b95b2f"> |

<br />

## 라우터 설정

| 경로              | 설명           |
| ----------------- | -------------- |
| /                 | 홈             |
| /company/interest | 관심 종목      |
| /company/ipo      | IPO 일정       |
| /company/detail   | 기업 상세 정보 |
| /news             | 뉴스           |
| /search           | 검색           |
| /supports         | 고객 지원      |

<br />

## 페이지 설계

<br />

## 컴포넌트 설계

### Header 컴포넌트

| 디자인                                                                                                                                       | 구성                                                                                                                                       | 기능                                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| <img width="700" alt="Header 컴포넌트 디자인" src="https://github.com/devkmins/Stomaw/assets/59950909/0b7db577-3e33-4d0b-8452-8266aaa7ebd7"> | <img width="700" alt="Header 컴포넌트 구성" src="https://github.com/devkmins/Stomaw/assets/59950909/0cacabac-9450-4fb4-b398-05ab0e7cec27"> | <img width="700" alt="Header 컴포넌트 기능" src="https://github.com/devkmins/Stomaw/assets/59950909/f3078d32-00e2-48be-ad29-aad9dc4b5a7a"> |

<br />

### SideBar 컴포넌트

| 디자인                                                                                                                                        | 구성                                                                                                                                        | 기능                                                                                                                                        |
| --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="SideBar 컴포넌트 디자인" src="https://github.com/devkmins/Stomaw/assets/59950909/52450eae-b815-4147-b024-7cd0887da75f"> | <img width="700" alt="SideBar 컴포넌트 구성" src="https://github.com/devkmins/Stomaw/assets/59950909/d41f4367-486f-4763-8ed0-08617fac00b3"> | <img width="700" alt="SideBar 컴포넌트 기능" src="https://github.com/devkmins/Stomaw/assets/59950909/2c349166-cdc5-41cf-8205-eba658da4a34"> |

<br />

### HeaderTitle 컴포넌트

| 디자인                                                                                                                                            | 구성                                                                                                                                            | 기능                                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="700" alt="HeaderTitle 컴포넌트 디자인" src="https://github.com/devkmins/Stomaw/assets/59950909/a6e07c96-9b2e-4e62-b158-6817cdb898b8"> | <img width="700" alt="HeaderTitle 컴포넌트 구성" src="https://github.com/devkmins/Stomaw/assets/59950909/d12375bd-445f-4b9c-9d08-25e5182a67fe"> | <img width="700" alt="HeaderTitle 컴포넌트 기능" src="https://github.com/devkmins/Fico/assets/59950909/618a288b-d3ee-4ad3-b96e-ce7c541c4a92"> |

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

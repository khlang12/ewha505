# MEP – Must-eat Place, Make Experience  
*A campus-based food experience platform focused on sharing moments, not just restaurants.*
![MEP Project Overview](assets/01-overview.jpg)
<br>

---

<br>

## 프로젝트 개요 (Overview)
![Service Name & Concept](assets/03-service-name.jpg)
**MEP (Must-eat Place, Make Experience)** 는  
대학가 주변 맛집을 단순히 탐방하는 것을 넘어,  
식사 경험 자체를 기록하고 공유하는 **경험 중심의 맛집 플랫폼**을 목표로 한 웹 서비스입니다.

- 프로젝트 기간: **2022.09 – 2022.12**  
- 팀명: **Ewha505**  
- 프로젝트 성격: 팀 프로젝트 (대학교 전공 수업)  
- 대상 사용자: 대학생 및 캠퍼스 방문자  

<br>

MEP is a campus-based web service designed to frame dining  
not merely as consumption, but as an **experience worth sharing**.

- Project period: **Sep 2022 – Dec 2022**  
- Team: **Ewha505**  
- Type: Team-based academic project  
- Target users: University students and campus visitors  

<br>

---

<br>

## 문제 정의 (Problem)

대학가 맛집 정보는 블로그, SNS, 지도 서비스 등 여러 채널에 분산되어 있어  
사용자가 **위치와 경험을 기준으로 빠르게 비교하기 어렵다**는 문제가 있습니다.

기존 서비스는 정보 나열에 집중되어 있어,  
사용자가 실제로 느낀 '**경험의 맥락**'을 파악하기 어렵다고 판단했습니다.

<br>

Food-related information around university areas is fragmented across blogs, SNS, and map platforms.  
This makes it difficult for users to compare options based on **both location and experience**.

Existing services prioritize listings over experiential context.

<br>

---

<br>

## 해결 방식 (Solution)

MEP는 맛집 정보를 단순히 보여주는 것을 넘어,  
**경험을 중심으로 한 사용자 참여형 플랫폼**을 지향했습니다.

<br>

MEP approaches food discovery as a **shared experience**,  
rather than a static list of restaurants.

<br>

### 주요 기능
- 회원가입 및 로그인  
- 지도 및 리스트 기반 맛집 탐색  
- 맛집 및 메뉴 등록  
- 리뷰 작성 및 평균 별점 자동 반영  
- 카테고리 기반 탐색 (예: 디저트)  
- ‘쩝쩝박사 코스’를 통한 사용자 경험 공유  

기능 확장보다 **사용자 흐름의 명확성과 서비스 컨셉 유지**를 우선했습니다.

<br>

### Key Features
- User authentication (sign up / login)  
- Map- and list-based restaurant exploration  
- Restaurant and menu registration  
- Review system with dynamic average ratings  
- Category-based browsing  
- Curated food “course” feature for sharing experiences

The service prioritizes **clarity of user flow and consistency of concept** over feature breadth.

<br>

---

<br>

## 기술적 접근 (Technical Approach)
![Development Environment & Tech Stack](assets/04-development-environment.jpg)
- **HTML / CSS / JavaScript**  
  서비스 구조를 명확히 드러내고 빠른 구현을 위해 사용  

- **React**  
  UI 컴포넌트 재사용성과 상태 관리 효율을 고려해 적용  

- **지도 API 연동**  
  위치 기반 탐색이 핵심 요구사항이었기 때문  

<br>

기술 선택은 학습 목적이 아닌,  
**서비스 요구사항과 구현 범위에 적합한지**를 기준으로 결정했습니다.

<br>

- **HTML / CSS / JavaScript**
  Used to clearly define the service structure and enable rapid implementation  
within the given project timeline.

- **React**
  Applied to improve UI component reusability and state management efficiency.

- **Map API Integration**
  Adopted because location-based exploration was a core requirement of the service.

<br>

All technical decisions were made based on  
**service requirements and implementation scope**, rather than experimentation.

<br>

---

<br>

## 데이터베이스 구성 (Database Structure)
![Database Structure](assets/05-database.jpg)

MEP는 **Firebase Realtime Database**를 사용하여  
서비스에서 생성되는 데이터를 실시간으로 관리합니다.

각 데이터는 서비스 흐름과 사용자 경험을 기준으로 분리되어 있으며,  
중복을 최소화하고 조회 효율을 높이는 구조로 설계했습니다.

<br>

### 데이터 구성
- **foodcourse**  
  사용자가 직접 구성하는 ‘쩝쩝박사 코스’ 데이터 저장  

- **restaurant**  
  맛집 기본 정보 및 위치 데이터 저장  

- **menu**  
  각 맛집에 속한 메뉴 정보 저장  

- **review**  
  사용자 리뷰 및 별점 데이터 저장  
  (리뷰 작성 시 평균 별점 자동 반영)

- **user**  
  사용자 계정 및 활동 정보 저장  

<br>

The service uses **Firebase Realtime Database** to manage data in real time.

Data is separated by domain (course, restaurant, menu, review, user)  
to maintain clarity, scalability, and efficient access based on user flow.

<br>

---

<br>

## 역할 및 기여도 (Role & Contribution)

### 팀 구성
- **팀장**: 임가현  
- **팀원**: 이유진, 서지민, 한수지, 성원희  

### 담당 역할
- 프로젝트 전체 기획 및 일정 관리  
- 서비스 구조 및 사용자 흐름 설계  
- 핵심 기능 및 화면 흐름 구현  
- 기술 스택 및 구현 범위에 대한 의사결정  
- 팀 내 협업 조율 및 진행 관리  

팀장으로서 **기획–개발–협업 전반을 조율하며 프로젝트를 리딩**했습니다.

<br>

### Team Structure
- **Team Lead**: Lim Kahyun  
- **Team Members**: Lee Yujin, Seo Jimin, Han Suji, Sung Wonhee  

### Responsibilities
- Led overall project planning and schedule management  
- Designed the service architecture and user flow  
- Implemented core features and screen flows  
- Made decisions on the technical stack and implementation scope  
- Coordinated collaboration and managed team progress

<br>

---

<br>

## 결과 및 인사이트 (Outcomes & Learnings)

- 기능 중심이 아닌 **경험 중심 서비스 설계의 중요성**을 체득  
- 사용자 흐름을 기준으로 기능 우선순위를 정하는 개발 방식 학습  
- 소규모 팀에서의 기술적 의사결정과 리더십 경험  

<br>

- Experience designing a service from problem definition to implementation  
- Strong focus on user flow, scope control, and concept consistency  
- Hands-on leadership experience in a small technical team  

<br>

---

<br>

## 프로젝트 배경 (Context)

본 프로젝트는 **이화여자대학교 컴퓨터공학과 「오픈SW플랫폼」 수업**의 팀 프로젝트로 진행되었습니다.

과제 결과물 자체보다는, **서비스 관점에서의 문제 정의와 프로젝트 리딩 경험**을 보여주기 위해 공개되어 있습니다.

<br>

This project was completed as part of the **Open Source Software Platform** course  
in the Department of Computer Science & Engineering at Ewha Womans University.

It is included here to demonstrate **service-oriented thinking and project leadership**,  
rather than as a production-ready system.

<br>

---

<br>

## 실행 방법 (Run Locally)

```bash
git clone https://github.com/khlang12/ewha505.git
# Open index.html in a browser
```

<br>

---

<br>

## 데모 영상 Demo
https://drive.google.com/file/d/1tXzu8Rs0H4BySpcns1kJAqVRhBPeL_-l/view

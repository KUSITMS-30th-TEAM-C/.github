# 🧩 조각조각

# 🕊️ Developers

| <img src="https://github.com/user-attachments/assets/9348e51b-8d12-46d9-98d2-f22769bc56b6" width="220" height="220" /> | <img src="https://github.com/user-attachments/assets/d0d6bc93-7648-4200-8329-735e77d71170" width="220" height="220" /> | <img src="https://github.com/anxi01.png" width="220" height="220" /> | <img src="https://github.com/HoyeongJeon.png" width="220" height="220" /> |
|:----------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------:|:--------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
|                                          [황동준](https://github.com/nebulaBdj)                                           |                   [공예영](https://github.com/yeyounging)                   |                   [한성민](https://github.com/anxi01)                   |                   [전호영](https://github.com/HoyeongJeon)                   |
|                                                     Frontend Lead                                                      |                              Frontend                               |                             Develop Lead                             |                                  Backend                                  |
<br><br>

# 🏛️ System Architecture
![조각조각_시스템_아키텍처](https://github.com/user-attachments/assets/7ddb4d40-184f-4f2f-88f7-42d908c69fcb)
<br><br>


# 🧱 ERD
![조각조각_ERD](https://github.com/user-attachments/assets/db743475-600c-42d6-a9fa-d9e7f5235718)
<br><br>


# 📝 API 명세서
<div style="text-align: center;">
    <a href="https://cnergy.p-e.kr/swagger-ui/index.html" target="_blank">
        <img src="https://github.com/user-attachments/assets/eb66d2b3-0dae-4a62-b9e3-edd52450c3e6" alt="Swagger API Docs" style="width: 100px; height: 100px;">
    </a>
    <br>
</div>
<br><br>
<div style="text-align: center; margin-top: 10px;">
    <a href="https://1na0s.notion.site/API-3d04a7512ddc45b8bf67ca6f60d515b0?pvs=74" target="_blank">
        <img src="https://github.com/user-attachments/assets/6de3056d-2e4f-4ef9-a5a0-34103aaef47c" alt="Notion API Docs" style="width: 100px; height: 100px;">
    </a>
    <br>
</div>
<br><br>

# ✏️ Naming Rules

## 🖥️ Frontend

> 모든 코드는 **lowerCamelCase** 로 작성한다
- 상수: `UPPERCASE_UNDERBAR` (모든 글자를 대문자로, 단어 사이에 **언더바(_)** 사용)

## 🖥️ Backend

> 패키지와 클래스를 제외한 모든 코드는 **lowerCamelCase** 로 작성한다
- 패키지: `lowercase` (소문자)
- 클래스: `UpperCamelCase` (첫 글자와 단어마다 대문자)
- 변수, 메서드: `lowerCamelCase` (첫 글자는 소문자, 이후 단어는 대문자)
- 상수: `UPPERCASE_UNDERBAR` (모든 글자를 대문자로, 단어 사이에 **언더바(_)** 사용)
<br><br>

# 📝 Commit Convention

## 🖥️ Frontend
> “커밋타입: 작업 내용”
ex) feat: 온보딩 페이지

## 📌 Commit Type
| Type | 뜻 |
| --- | --- |
| feat | 새로운 기능을 추가할 경우 |
| fix | 버그를 고친 경우 |
| docs | 문서를 수정한 경우 |
| style | 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우 |
| refactor | 프로덕션 코드 리팩토링 |
| design |  CSS 등 사용자 UI 디자인 변경 |
| chore |  그 외 자잘한 수정 |
| test | 테스트 코드 작성 |
| HOTFIX | 급한 버그 수정 (main에서 수정하는 경우) |
| setting | 환경설정 |

## 🖥️ Backend
> “커밋타입: (#이슈번호) 작업 내용”
ex) feat: (#13) Google, Naver, Kakao의 RestClient 구현체를 구현한다

## 📌 Commit Type
| Type | 뜻 |
| --- | --- |
| feat | 새로운 기능 추가 |
| fix | 버그 수정 및 기능 수정 |
| refactor | 코드 리팩토링 |
| chore | 그 외 자잘한 수정 |
<br><br>

# 💨 Git Flow
![Git Flow](https://github.com/user-attachments/assets/1666715f-5f2a-4f45-beee-d909cb5f4cf9)
- **main**: 출시 가능한 **프로덕션 코드**를 관리하는 브랜치
- **develop**: 다음 버전을 위한 **개발 작업**이 이루어지는 브랜치
- **feat**: 이슈 단위로 **새로운 기능**을 개발하는 브랜치
    - 브랜치 네이밍: `feat/#이슈번호-작업내용`
- **fix**: 이슈 단위로 **버그 수정**을 진행하는 브랜치
    - 브랜치 네이밍: `fix/#이슈번호-작업내용`

(프론트엔드는 **main**, **feat**, **fix** 브랜치만 사용)
<br><br>

# 🖥️ Frontend

## 기술 스택
- Next.js 14
- React 18
- Tailwind CSS
- eslint - airbnb , prettier
- 테스트 라이브러리 : Storybook & Jest
- 데이터페칭 : axios, tanstack-query, contextAPI
- 전역관리 : zustand
- 애니메이션 : Framer motion
- CI/CD : github actions, NCP, docker

## 선정 이유
- **Next.js**
  - **서버 사이드 렌더링(SSR)** 및 **정적 사이트 생성(SSG)** 지원으로 SEO 향상과 빠른 페이지 로딩 제공.
  - **Full-stack 기능** 제공으로 API 라우팅과 프론트엔드를 통합할 수 있어 효율적인 개발 가능.
  - **Edge Functions**와 같은 최신 성능 최적화 기능을 활용할 수 있음.
- **React 18**
  - **Concurrent Mode**를 통해 성능을 향상하고, 대규모 애플리케이션에서 더욱 부드러운 UI 렌더링.
  - 최신 **Hook 기반 API**로 코드 간결성 및 상태 관리 향상.
  - 커뮤니티와 생태계가 매우 크고, 다양한 서드파티 라이브러리와의 호환성이 좋음.
- **Tailwind CSS**
  - **유틸리티 우선 CSS 프레임워크**로, 빠르게 일관된 스타일링 가능.
  - 클래스 단위로 CSS를 관리하기 때문에 유지보수성이 높고, 불필요한 CSS 코드 생성을 최소화.
  - 커스텀 디자인을 쉽게 적용하면서도 **반응형 디자인**을 유연하게 구현할 수 있음.
- **eslint - airbnb**
  - **코드 스타일 일관성**을 유지하고, **버그를 예방**하기 위해 AirBnB 스타일 가이드를 활용한 Linting 도구.
  - 코드 품질 향상과 팀 간 협업 시 일관된 코딩 스타일을 유지.
- **Prettier**
  - **자동 코드 포매팅**을 통해 코드 스타일을 일관되게 유지.
  - 개발자의 생산성 향상과 코드 리뷰 시 시각적 노이즈를 줄일 수 있음.
- **Storybook**
  - **UI 컴포넌트 개발 및 테스트 도구**로, 컴포넌트 단위 개발을 효율적으로 진행.
  - **디자인 시스템**을 관리하고, 컴포넌트 간의 재사용성을 높임.
- **Jest**
  - **테스트 프레임워크**로, 단위 테스트 및 통합 테스트 작성에 용이.
  - Mocking, Snapshot Testing, Code Coverage 기능을 통해 철저한 테스트 환경 제공.
  - storybook을 함께 이용해 TDD 방식에 적용
- **TanStack Query & ContextAPI**
  - 효율적인 비동기 처리를 위해 사용
- **CI/CD (GitHub Actions, NCP, Docker)**
  - **GitHub Actions**: 코드 변경 시 자동화된 빌드, 테스트, 배포 파이프라인을 설정하여 개발 프로세스의 효율성 증대.
  - **NCP (Naver Cloud Platform)**: 안정적인 인프라 제공 및 한국 지역 기반 서비스 운영 시 유리.
  - **Docker**: 개발 환경을 컨테이너화하여 일관성 있는 환경에서 애플리케이션 배포 가능.
- **Zustand**
  - **가벼운 상태 관리 라이브러리**로, Redux보다 간단하고 코드가 간결해지며, 리액티브한 글로벌 상태 관리에 적합.

## 시연 영상

https://github.com/user-attachments/assets/143d7d82-852f-4c9a-a71d-814e3dc2e795



## AsyncBoundary+tanstack-query를 이용한 데이터 페칭
- tanstack-query를 이용한 데이터 캐싱
- SSR환경에서 사용 가능한 Suspense 구현
- AsyncBoundary를 통한 비동기 데이터페칭 에러/로딩 상태 선언적 관리
- AsyncBoundaryWithQuery 구현 : tanstack-query의 useQueryErrorResetBoundary를 활용하여 데이터 페칭 중 오류 발생 시 데이터를 다시 가져옵니다.
<br><br>

# 🖥️ Backend

## 기술 스택
- **Java 17**
- **Spring Boot 3.3.4**
- **Spring Data JPA**
- **Spring Security / OAuth2**
- **MySQL 8.x**
- **Docker**
- **Github Actions**
- **Naver Cloud Platform**
- **Sentry (로그 관리)**
- **Swagger**

## 선정 이유
- **Java 17**
  - LTS(Long-Term Support) 버전으로 2029년 9월까지 지원합니다.
  - 최신 LTS 버전인 JDK21을 바로 사용하는 것보다 그 전 LTS 버전인 JDK 17을 사용하여 추후 JDK 21로 마이그레이션시 영향을 줄일 수 있기 때문입니다.
  - Spring Boot 3.0부터는 JDK 17 이상부터 지원하므로 JDK17을 사용하였습니다.
- **Spring Boot 3.3.4**
  - 이번 프로젝트에서 WebSocket을 이용한 채팅 기능을 구현할 것으로 보이는데, Spring Boot 3.3 버전부터 WebSocket을 위한 가상 스레드 지원을 하기 때문에 가상 스레드의 동시섬 이점을 활용하여 WebSocket 통신이 효율적으로 처리될 수 있어 사용하게 되었습니다.
- **Spring Data JPA**
  - SQL을 직접 작성하지 않고 객체지향적인 코드로 데이터베이스를 다루기 위해서 JPA를 사용하고, Spring 프레임워크에서 JPA를 쉽게 사용할 수 있는 모듈인 Spring Data JPA를 지원하기 때문에 사용하였습니다.
- **Spring Security / OAuth2**
  - Spring Security를 사용하여 인증과 인가를 체계적으로 관리할 수 있습니다. 특히 다양한 인증/인가 방식을 제공하는데 다양한 소셜 로그인 구현에 적합한 OAuth2를 Spring Security에서 제공하기 때문에 사용하였습니다.
- **MySQL 8.x**
  - 5 버전에 비해 향상된 성능, 강화된 보안 기능, 공간 데이터 처리 등을 사용하기 위해 사용했습니다.
- **Docker**
  - 개발 및 배포 환경을 쉽게 컨테이너화하기 위해서 사용하였습니다.
- **Github Actions**
  - Github와 하나로 통일된 환경에서 CI를 수행하기 위해 사용하였습니다.
- **Naver Cloud Platform**
  - 한국에서 만든 클라우드 서비스로 서버, AI 등 프로젝트에 필요한 서비스를 사용하였습니다.
- **Sentry (로그 관리)**
  - 에러 로그 모니터링과 중앙집중적 에러 로그 관리를 위해 사용하였습니다.
- **Swagger**
  - 클라이언트, 서버 간 API 명세서 용도로 사용하였습니다.

## NCP 사용 스택
- **Server**
  - 백엔드 배포 서버로 사용했습니다.
  - 프론트엔드 배포 서버로 사용했습니다.
- **VPC**
  - 클라우드 내 전용 네트워크를 확보하기 위해 VPC를 사용했습니다.
  - 현재 프론트엔드와 백엔드가 하나의 VPC내 다른 Subnet으로 구성되어있습니다.
  - 추후 백엔드 Subnet을 Private으로 설정해 외부접근을 제한하고, 프론트엔드 서버를 통해서만 접근할 수 있도록해 보안을 강화할 예정입니다.
- **Container Registry**
  - 백엔드 및 프론트엔드 모두 Docker를 사용해 배포를 진행합니다. Public Registry에 이미지를 저장할 경우, 민감한 정보들을 관리하기 어렵기에 사설 Registry인 NCP Container Registry를 사용했습니다.
  - Container Registry 의 경우 레지스트리에 등록된 이미지의 취약점을 분석해 정보를 제공해줍니다. 이를 통해 컨테이너의 취약점을 제거해 컨테이너를 더욱 안전하게 사용할 수 있습니다.
- **Naver Clova Studio**
  - 한국 사람들이 가장 많이 사용하는 검색엔진의 데이터를 활용하여 개발되었기 때문에, 한국 사용자에게 활동을 추천하는 프로젝트에 적합하다 판단해 사용합니다.
  - 사용자에게 현재 상황과 취향을 입력받아 활동 추천 시 Clova AI를 사용합니다.
  - 모델을 튜닝하여 사용자에게 다양한 활동을 추천합니다.
<br><br>

# 🙋 질문있어요!

## ❓ Frontend

#### Q. 컴포넌트 설계시 비즈니스 로직을 분리하는 것이 무조건 지향해야 하는 방향인지 궁금합니다. 

비즈니스 로직을 분리하느라 공통 컴포넌트는 각각 index.tsx, use훅을 포함하는 폴더로 구성했습니다. 

그리고 공통 컴포넌트가 아닌 다른 컴포넌트들은 비즈니스 로직 분리가 굳이 필요 없는것 같아서 단일 파일 형태로 구성해 놨는데 하나로 통일하는게 좋을까요?

#### Q. 한 페이지에서 많은 상태관리가 필요한 경우(폼 작성 등)와 상태의 변경에 따라 API 호출도 필요한 경우 비즈니스 로직을 어떻게 분리하는 것이 좋은지 궁금합니다.

훅은 하나의 상태관리에 대해 책임을 지는 것이 좋다고 들었는데, 그렇다면 하나의 상태값마다 각각의 훅을 분리된 파일로 정의하는 것인지 궁금합니다.

#### Q. 분기 처리 관련 질문이 있습니다. 

실무에서 분기 처리를 해야 하는 경우가 매우 많아서 종속적인 else if나 else보다 if만 이용해서 처리하는게 가독성 측면에서 더 좋다고 들었는데, 실제로 그런지와 유용한 분기처리 방식이 궁금합니다.

## ❓ Backend

#### Q. 저희 서비스는 사용자의 자투리 시간을 의미있게 보낼 수 있도록 활동을 추천해주는 서비스입니다. 현재 ClovaStudio를 통해 활동을 추천하려고 합니다. 

문제는 현재 ClovaStudio가 추천해주는 내용이 범용적이라는 점입니다.

```json
{
    "success": true,
    "timestamp": "2024-11-03T19:09:32.054046",
    "data": [
        {
            "order": 1,
            "title": "트위터에서 관심사 해시태그 팔로우 하기 https://twitter.com/",
            "content": "짧은 시간에 다양한 소식을 받아볼 수 있어요!",
            "keywordCategory": "SOCIAL"
        },
        {
            "order": 2,
            "title": "인스타그램 둘러보기 탭에서 인기 게시물 확인하기 https://www.instagram.com/explore/",
            "content": "시각적인 자극으로 트렌드를 파악할 수 있어요!",
            "keywordCategory": "SOCIAL"
        },
        {
            "order": 3,
            "title": "유튜브 쇼츠에서 유행하는 밈 찾아보기 https://youtube.com/shorts",
            "content": "숏폼 콘텐츠로 쉽고 빠르게 즐길 수 있어요!",
            "keywordCategory": "SOCIAL"
        },
        {
            "order": 4,
            "title": "페이스북 페이지 좋아요 누르고 최신 소식 받아보기 https://www.facebook.com/",
            "content": "긴 글도 부담 없이 읽을 수 있어요!",
            "keywordCategory": "SOCIAL"
        },
        {
            "order": 5,
            "title": "카카오톡 오픈채팅방에서 관심사 주제로 대화 나누기 https://open.kakao.com/",
            "content": "실시간으로 사람들과 소통할 수 있어요!",
            "keywordCategory": "SOCIAL"
        }
    ]
}
```

위와 같이 추천이 되면 사용자가 직접 활동을 찾아야하는 것과 다름없기에 구체적인 추천을 원하는 상태입니다.

쇼츠보기! 가 아닌 특정 쇼츠 보기, 카카오톡 오픈채팅방에서 관심사 주제로 대화 나누기! 가 아닌 특정 오픈채팅방의 링크와 함께 추천을 해주는 방식으로 구현하려 합니다.

생성형 AI를 통한 추천의 경우 구체적인 내역이 나오지를 않는데, 이를 해결하기 위한 다른 방법이 무엇이 있을지 궁금합니다.

최우선적으론 생성형 AI를 통해 구체적인 링크까지 추천을 원하지만, 이 외에도 크롤링을 통해 구체적인 링크를 DB에 저장해 사용자에게 보내주는 방식도 고려하고 있습니다.
사용자에게 의미있는 활동 추천을 어떻게 해야할지 피드백을 원합니다.

#### Q. 로깅을 할 때 로깅을 어떻게 저장하는 것이 좋을지 궁금합니다. 

로깅을 파일 또는 DB에 저장을 할 수도 있고, Sentry와 같은 서비스를 이용할 수도 있는데 현업에선 어떤 방식을 활용하는지 궁금합니다.

#### Q. 프로젝트의 품질을 향상하고 싶습니다.

추천 시스템이 주된 기능입니다.

이외 기능은 CRUD 구현 정도인데 간단한 기능이라도 프로젝트의 품질을 높이는 방법이 궁금합니다.

예를 들어, 저희는 도메인 별 로직을 분리하기 위해 도메인 주도 개발 방법론(DDD)을 현재 프로젝트에 적용하고 있습니다.

DDD 외에 프로젝트나 CI/CD 등 개발적으로 프로젝트 품질을 향상하고자 한다면 어떠한 방법이 있을지 여쭈고 싶습니다.

# Budget-Guardian
예산 관리 서비스 💸

## 개요
본 서비스는 사용자들이 개인 재무를 관리하고 지출을 추적하는 데 도움을 주는 애플리케이션입니다.  
이 앱은 사용자들이 예산을 설정하고 지출을 모니터링하며 재무 목표를 달성하는 데 도움이 됩니다. 

<br />

## 개발 환경

```
• IDE : IntelliJ IDEA Ultimate
• 언어 : Java 17
• 프레임워크 : Spring Boot 3.1.5
• 빌드 도구 : Gradle
• 데이터베이스 : MySQL 8.0 + Docker Build
```

## 사용 기술

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Spring Boot 3.1.5-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white"/></a>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Spring Data JPA-gray?style=for-the-badge&logoColor=white"/></a>
<img src="https://img.shields.io/badge/QueryDSL-0078D4?style=for-the-badge&logo=Spring Data JPA&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MySQL 8-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Junit-25A162?style=for-the-badge&logo=JUnit5&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Mockito-6DB33F?style=for-the-badge"/></a>

<br />

## ERD

<img src = "https://github.com/min050410/Budget-Guardian/assets/45661217/c6437f87-a5af-492a-9cbb-deb65d381bfc" width="500" />

<br />

## UseCase

- A. 유저는 본 사이트에 들어와 회원가입을 통해 서비스를 이용합니다.
- B. 예산 설정 및 설계 서비스
    - `월별` 총 예산을 설정합니다.
    - 본 서비스는 `카테고리` 별 예산을 설계(=추천)하여 사용자의 과다 지출을 방지합니다.
- C. 지출 기록
    - 사용자는 `지출` 을  `금액`, `카테고리` 등을 지정하여 등록 합니다. 언제든지 수정 및 삭제 할 수 있습니다.
- D. 지출 컨설팅
    - `월별` 설정한 예산을 기준으로 오늘 소비 가능한 `지출` 을 알려줍니다.
    - 매일 발생한 `지출` 을 `카테고리` 별로 안내받습니다.
- E. 지출 통계
    - `지난 달 대비` , `지난 요일 대비`,  `다른 유저 대비` 등 여러 기준 `카테고리 별` 지출 통계를 확인 할 수 있습니다.

## 🏷️ API

#### Member(사용자, 인증)

<img width="1432" alt="image" src="https://github.com/min050410/Budget-Guardian/assets/45661217/17b4af4a-8bb1-41d9-aacc-0c892d073249">


#### Category(카테고리)

<img width="1430" alt="image" src="https://github.com/min050410/Budget-Guardian/assets/45661217/179767e8-8e84-431c-88ea-3fb86a87fc32">


#### Budget(예산)

<img width="1433" alt="image" src="https://github.com/min050410/Budget-Guardian/assets/45661217/8ccc9d1f-fec1-4fbb-8eb2-2bb0e29261f4">


#### Expenditdure(지출)

<img width="1433" alt="image" src="https://github.com/min050410/Budget-Guardian/assets/45661217/9647f4ee-8a2d-43aa-b8fd-8994d9ed7310">

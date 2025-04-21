# 나만의 화학 실험실 ATOMIX
본 레포지토리는 2025.04.19 ~  2025.04.20 STDev 해커톤 백엔드 서버 입니다.
## Index
  - [프로젝트 소개](#프로젝트-소개)
  - [주요 기능](#주요-기능)
  - [기술 스택](#기술-스택)
  - [실행 방법](#실행-방법)
  - [데모](#데모)
  - [팀원 소개](#팀원-소개)
  - [프로젝트 구조](#프로젝트-구조)
  - [해커톤 회고](#해커톤-회고)
---
## 프로젝트 소개
**나만의 화학 실험실 ATOMIX**는 초,중,고 학생을 대상으로한 화학 교육 목적의 서비스 입니다. 

ATOMIX는 아래와 같은 목적으로 시작하였습니다:

- 모든 것이 디지털화 되는 시대에서 화학 실험 또한 디지털화 시켜보면 어떨까?
- 접근성을 높여 지역별 교육 격차를 해소할 수 있지 않을까?
- 어떻게 하면 학생들이 화학 수업을 즐겁게 할 수 있을까?

이러한 문제점들을 해결하기 위해, ATOMIX는 다양한 화학 실험을 가상 환경에서 안전하게 수행할 수 있는 플랫폼을 제공합니다. 사용자는 원소 조합, 화학 반응 시뮬레이션, 분자 구조 시각화 등을 통해 화학의 기본 원리를 직관적으로 이해할 수 있으며 1:1 대전을 통해 물질의 특성을 빠르게 파악하고 자연스럽게 익힐 수 있도록 합니다

본 백엔드 서버는 화학 물질 데이터 처리, 사용자 정보 관리, 그리고 프론트엔드와의 통신을 담당합니다


---
## 주요 기능
ATOMIX는 다음과 같은 주요 기능을 제공합니다:
1. 원소 및 분자 시각화 - 주기율표의 원소들과 분자식을 시각화하여 학생들의 이해를 돕습니다.
2. 다양한 상호작용 - 학생들이 직접 원소들을 조합하여 물질을 만들어냅니다. 이를 통해 뜻밖의 물질을 발견할 수 있으며 호기심을 자극하고 물질의 구조와 원리를 자연스럽게 습득할 수 있도록 유도합니다.
3. 게임형 학습 - 습득한 원소들을 활용하여 물질을 제작하고, 이를 통해 친구들과 1:1 대전을 펼칩니다. 화학식을 많이 알 수록 유리하게 설계되어 있어 경쟁심을 유도하고 게임을 플레이할 수록 점점더 많은 화학식을 익힐 수 있게 됩니다.
4. 도감 - 조합에 성공한 물질들은 도감에 기록되며 관련된 정보를 손쉽게 확인할 수 있습니다
5. 랭킹 시스템 - 발견한 물질이 많을 수록 상위에 랭크됩니다. 또한 그룹별 랭킹 시스템을 적용하여 자신의 학교가 전국에 몇위에 위치하는지를 알 수 있어 경쟁심을 자극합니다.
6. 상점 : 서비스 내 포인트가 존재하며 대전에서 승리 하거나 광고 시청 시 지급됩니다. 포인트로는 원소를 해금하거나 다양한 아이템들을 구매할 수 있습니다


---
## 기술 스택

### 백엔드
- ![Java](https://img.shields.io/badge/Java-17-orange)
- ![Spring Boot](https://img.shields.io/badge/Spring_Boot-2.7.0-green)
- ![JPA](https://img.shields.io/badge/JPA-Hibernate-brightgreen)
- ![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)

### 인프라
- ![AWS](https://img.shields.io/badge/AWS-EC2-orange)

### 개발 도구
- ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2024.1-purple)
- ![Postman](https://img.shields.io/badge/Postman-API_Testing-orange)

### 협업 툴
- ![Git](https://img.shields.io/badge/Git-2.36-red)
- ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

### 문서화
- ![Swagger](https://img.shields.io/badge/Swagger-API_Docs-green)

  
---
## 실행 방법

### 사전 요구사항
- JDK 17
- Gradle 8.13
- MySQL 8.0
- Spring Boot 3.4.4

### 로컬 환경에서 실행
1. 레포지토리 클론
```bash
git clone https://github.com/hongjunpyo123/STDev-Hackthon-Team-10-backend.git
cd team10
```

2. properties 설정
```bash
spring.datasource.url=jdbc:mysql://localhost:8080/team10
spring.datasource.username=your-username
spring.datasource.password=your-password
```

3. 프로젝트 빌드 및 실행
```bash
./gradlew build -x test
java -jar ../team10-0.0.1-SNAPSHOT.jar
```

---
## 데모

현재 서비스는 해커톤 이후로 중단되었습니다.

### 스크린샷
![메인 화면](https://github.com/user-attachments/assets/e30cd0ea-5b72-4bae-bd78-0729c42fa4e8)
![싱글 플레이](https://github.com/user-attachments/assets/c309c07c-7a6e-4f47-862a-a85570b167f3)
![화합물 발견](https://github.com/user-attachments/assets/c15f1400-e957-44bd-be95-36fd6a254ce2)
![멀티 플레이-1](https://github.com/user-attachments/assets/f0a039bc-750c-49d9-8c89-dc3580ef515f)
![멀티 플레이-2](https://github.com/user-attachments/assets/268f7bfd-2e89-4903-81b8-9cf56f0a18ab)
![멀티 플레이-3](https://github.com/user-attachments/assets/681c74e7-2f3d-4ffb-8b6f-d29340215f11)
![멀티 플레이-4](https://github.com/user-attachments/assets/2ddd2091-1c6f-4474-a60f-f9e449d6b567)
![도감](https://github.com/user-attachments/assets/1b84237e-768f-497e-80d8-c8dcae6f75ac)
![랭킹](https://github.com/user-attachments/assets/5293346a-700a-40ef-8c66-5f94102f6b0b)
![상점](https://github.com/user-attachments/assets/71ab2ece-74a8-4c44-a801-50a54e662f92)

---
## 팀원 소개

### Backend Developer
<img src="https://github.com/hongjunpyo123.png" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@hongjunpyo123](https://github.com/hongjunpyo123)

<img src="https://github.com/moonjun1.png" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@moonjun1](https://github.com/moonjun1)
---
### Frontend Developer
<img src="https://github.com/ij5.png" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@ij5](https://github.com/ij5)

<img src="https://github.com/lnylnylnylny.png" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@nylnylnylny](https://github.com/nylnylnylny)


---
## 프로젝트 구조
```bash
ATOMIX-Backend/
├── src/
│   ├── main/
│   │   ├── java/com/stdev/team10/
│   │   │   ├── Team10Application.java
│   │   │   ├── domain/
│   │   │   │   ├── chemical/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── dto/
│   │   │   │   │   ├── entity/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── service/
│   │   │   │   ├── collection/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── service/
│   │   │   │   ├── group/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── dto/
│   │   │   │   │   ├── entity/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── service/
│   │   │   │   ├── point/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── dto/
│   │   │   │   │   ├── entity/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── service/
│   │   │   │   ├── ranking/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── dto/
│   │   │   │   │   ├── entity/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── service/
│   │   │   │   ├── report/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── dto/
│   │   │   │   │   └── service/
│   │   │   │   ├── title/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── dto/
│   │   │   │   │   ├── entity/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── service/
│   │   │   │   └── user/
│   │   │   │       ├── controller/
│   │   │   │       ├── dto/
│   │   │   │       ├── entity/
│   │   │   │       ├── repository/
│   │   │   │       └── service/
│   │   │   └── global/
│   │   │       ├── common/
│   │   │       │   └── response/
│   │   │       ├── config/
│   │   │       └── util/
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/com/stdev/team10/
│           └── Team10ApplicationTests.java
├── build.gradle
└── settings.gradle
```


---
## 해커톤 회고

### 느낀 점
- 욕심은 끝이 없다. 프로젝트가 완성되어 갈 수록 부족한 점이 자꾸 눈에 들어오기 때문에 이럴 수록 더더욱 MVP를 정의하고 구현하는 것이 중요하게 느껴졌다.
- 시간이 아무리 없어도 기획을 대충하면 다시 갈아엎어야 한다. 되도록이면 디테일한 부분들까지 고려해가며 만들어야 오히려 빠르다
- 소통이 너무나도 중요하다. 내가 현재 하려는 작업의 목적을 명확히 하고 이를 개발하기 전에 팀원과 공유해야 함을 느꼈다

### 개선할 점
- 서비스에서 포인트의 활용도를 높이고 싶다. 현재는 원소 구매 정도만 가능하지만 다양한 아이템들을 추가해보고 싶다.
- 개인적으로 1:1 대전 기능을 좀 더 발전시켰으면 좋겠다. 화려한 이펙트와 다양한 전투 방식들을 추가하면 훨씬 더 재밌어질 것 같다.














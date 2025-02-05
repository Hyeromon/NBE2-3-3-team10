# WashPang
프로그래머스 백엔드 데브코스 2회차 프로젝트 2(리펙토링) Team10의 repository

Java SpringBoot 프로젝트 -> [Java SpringBoot](https://github.com/prgrms-be-devcourse/NBE2-3-2-team10)

# 📖
## 기술 스택
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
<br>
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
<br>

## 프로젝트 요구사항
1.효율적 폴더 구조, 코드 컨벤션 선정 및 리팩토링
2. FE 템플릿 엔진 변경(JSP > Thymeleaf)
3. 커스텀 에러, 공통 응답 추가 및 반영
4. 전체 코드 Kotlin 마이그레이션

### [변경된 폴더구조]
![Image](https://github.com/user-attachments/assets/3a4a5242-95d2-466f-9470-b83b8c0830ec)


## 코틀린 전환 시 기대효과 및 장단점
### <전환 시 기대 효과 및 장점>
함수형 프로그래밍을 활용하여 코드 간결성 및 가독성 향상
모델 정의가 간결해지고, 타입 체크 및 캐스팅이 용이해짐
기존의 이스케이프 문자를 제거하고 raw 문자열을 사용하여 불편함 감소
companion object의 정적 팩토리 메서드 (from)를 활용하여 클래스 인스턴스 생성 없이 JSON 데이터를 직렬화 가능

### <마주친 문제점 및 단점>
기존 Java 코드의 널 처리 로직을 Kotlin의 null safety 개념에 맞춰 수정해야 하는 번거로움
Java에서는 객체가 기본적으로 가변성인 반면, Kotlin에서는 불변성이 기본이라 객체를 다룰 때 가변성과 불변성의 의도를 명확히 맞춰야 하는 어려움


## KPT 회고
![Image](https://github.com/user-attachments/assets/81aa21ab-4f2f-4353-9982-2b624a813777)


### 브랜치 전략

#### 📋 Commit Message Convention 📋

| Tag | Description |
| --- | --- |
| `Feat` | 새로운 기능 추가 |
| `Fix` | 버그 수정 |
| `Docs` | 문서 추가, 수정, 삭제 |
| `Test` | 테스트 코드 추가, 수정, 삭제 |
| `Style` | 코드 형식 변경 |
| `Refactor` | 코드 리팩토링 |
| `Perf` | 성능 개선 |
| `Build` | 빌드 관련 변경사항 |
| `Ci` | CI 관련 설정 수정 |
| `Chore` | 기타 변경사항 |

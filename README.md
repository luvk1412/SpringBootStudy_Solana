# SpringBootStudy
## 스프링 부트 기초 사용법 스터디
### 진행자 : 김윤권, 장현석


## * 개요
- 기본적인 스프링 부트의 개념과 사용법을 익히기 위한 스터디 프로젝트로 기본적인 설정방법과 실무에서 자주쓰이거나 필요한 기술들을 스프링 부트를 사용해 편리하게 개발을 할 수 있도록 돕기위한 목적을 가진다.
- 기본적인 게시판 기능을 구현하며 사용자관리, 권한에 따른 접근관리, 실무에서 사용하는 프로젝트 관리(swagger,jenkins,github) 방법을 적용하며 실습한다.


## * 스프링이란?
- 스프링 프레임워크는 자바 생태계에서 가장 대중적인 응용프로그램 개발 프레임워크이다. 의존성 주입(DI, Dependency Injection)과 제어의 역전(IOC, Inversion Of Control)은 스프링에서 가장 중요한 특징중 하나이며 이들로 인해서 좀더 결합도를 낮추는 방식으로 어플리케이션을 개발할 수 있다. 이러한 개발방식을 통해 개발한 응용프로그램은 단위테스트가 용이하기 때문에 보다 퀄리티 높은 프로그램을 개발할 수 있다.

## * 왜 스프링이 아닌 스프링 부트인가?
    - 기존에 스프링은 어플리케이션을 개발하기위해서 관련된 설정들을 개발자가 직접 하나씩 설정해줘야하기 때문에 기본적으로 스프링을 사용하기위해 알아야하는 지식이 필요하고 이에따른 셋팅시간이 늘어나면서 개발기간이 의도치않게 딜레이되게 되는 상황이 빈번하게 생기는 현상이 생긴다.
    ex) Transaction Manager, Hibernate Datasource, Entity Manager, Session Factory와 같은 설정. 최소한의 기능으로 Spring MVC를 사용하여 기본 프로젝트를 셋팅하는데 개발자에게 너무 많은 시간이 걸린다.

    - 위와 같은 이유로인해 스프링 부트가 생겨났고 스프링 부트는 최소한의 설정으로 스프링에서 제공하는 기능들을 사용할 수 있게해주며 결과적으로 환경 설정을 최소화하고 개발자가 비즈니스 로직에 집중할 수 있게하여 생산성을 크게 향상시켜준다.



## * 스프링부트의 특징
    1. 독립 실행이 가능한 스프링 애플리케이션 개발 (Embedded Tomcat, Jetty, Undertow를 사용)
    2. 통합 Starter를 제공하여 Maven/Gradle 구성을 간소화 
    3. Starter를 통한 자동화된 스프링 설정 제공
    4. 번거로운 XML 설정을 요구하지 않음
    5. JAR을 이용하여 자바 옵션만으로도 배포 가능
    6. Spring Actuator 제공 (애플리케이션의 모니터링과 관리를 위해 사용) 


## * 스프링 부트의 장단점.

### [장점]
    - 각각의 의존성 버전을 수월하게 올리는 것이 가능
    - 스프링 부트의 버전이 올라갈 때마다 각 버전별 호환성에 대해 충분한 테스트를 거친 뒤 release
    - 기존에 각각 수동으로 설정했던 버전 관리에 비해서 안정된 버전 제공을 보장받을 수 있음
    - 간단한 어노테이션/프로퍼티 설정으로 원하는 기능을 빠르게 적용
    - 별도의 외장 톰캣을 설치할 필요가 없고 톰캣 버전도 편리하게 관리 가능
    - 특정 라이브러리에 버그가 있더라도 이후에 스프링팀으로부터 bugfix 된 버전을 받기에 편리함

### [단점]
    - 설정을 커스터마이징하는 경우 기존의 스프링 프레임워크를 사용하는 것과 같은 불편함이 있을 수 있음
    - 설정을 변경하고 싶은 경우 내부 코드를 살펴봐야하는 불편함이 있을 수 있음


## 개발환경
    - Github
        url : https://github.com/vusdlq007/SpringBootStudy/
    - jenkins
        url: (작성예정)
        계정: id/pwd
    - AWS RDS(mariaDB)
        ip/port: (작성예정)
        schema: (작성예정)
    - swagger : (작성예정)
    - AWS
        계정: id/pwd


## *스터디 진행사항 (총 6주)
### [2021-04-24 (토), 1주차 스터디 주제]
#### [시간 / 장소 : 00:00 / 오케스트로 여의도 본사 회의실]

    1. Spring boot 프로젝트 생성 (프론트 / 벡앤드)

    2. vue.js 문법 & 사용법 스터디.

    3. 주제 및 앞으로 진행계획 회의.
------------

### [2021-05-01 (토), 2주차 스터디 주제]
#### [시간 / 장소 : 00:00 / 오케스트로 여의도 본사 회의실]

    1. 아키텍처 구성 및 구현부분 할당, WBS 작성.

    2. JPA란? JPA 스터디 내용 공유.

    3. JPA 스터디를 위해 spring 내장 DB(H2) or 로컬에 mariaDB 설치 후 사용해서 JPA CRUD 실습.

    4. AWS EC2(nodeJs), RDS(mariaDB) 프리티어로 생성 및 기본 셋팅.
------------

### [2021-05-08 (토), 3주차 스터디 주제]
#### [시간 / 장소 : 00:00 / 오케스트로 여의도 본사 회의실]

    1. 사용자, 게시물 더미 데이터 설계 및 삽입.

    2. 간단한 화면 구현.
     - 프론트 : 로그인, 회원마이페이지, 관리자페이지, 게시판(페이징), 메인화면
     - 백엔드 : 로그인, 회원마이페이지, 관리자페이지, 게시판(페이징), 메인화면

    3. 코드리뷰.
------------

### [2021-05-15 (토), 4주차 스터디 주제]
#### [시간 / 장소 : 00:00 / 오케스트로 여의도 본사 회의실]

    1. JWT란? & JWT를 적용한 API 접근 서비스 구현.

    2. Spring Security란? & Spring Security를 적용한 권한 설정.

    3. 미정.

    4. 코드리뷰.
------------

### [2021-05-15 (토), 5주차 스터디 주제]
#### [시간 / 장소 : 00:00 / 오케스트로 여의도 본사 회의실]

    1. 미정.

    2. 미정.

    3. 코드리뷰.
------------

### [2021-05-15 (토), 6주차 스터디 주제]
#### [시간 / 장소 : 00:00 / 오케스트로 여의도 본사 회의실]

    1. 미정.

    2. 미정.

    3. 코드리뷰.

    4. 실제 프로젝트 주제 토의 & 회고록 작성.
------------

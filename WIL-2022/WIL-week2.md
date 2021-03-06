# WIL - 2022년 04월 25일 - 05월 1일 캠프 2주차


## 이번 주 한 일
<br>

    - 내일배움캠프 AWS 클라우드 배포환경 구축 기초
    - 내일배움캠프 웹프로그래밍 심화 A-Z (~2주차)
    - 개발 블로그 카테고리 정리
    - 정보처리기사 벼락치기 🥺

    + 내일배움캠프 AWS 클라우드 배포환경 숙제 구현
    + 나홀로일기장 코드 주석 달아보기
    + CSS flex 내용 정리
    + CSS margin, padding 내용 정리 (04.28 완료⭕)
    

<br>    

## 이번 주 목표
<br>

    1. 왜 AWS를 사용하며, 어떤 서비스를 사용할 수 있는지 알기  
        - 서버를 클라우드로 인해 빌려쓰는 형태로 변경되고 있는 추세다. 
        AWS는 Amazon에서 만든 클라우드 서비스로 클라우드 서비스 중에 제일 잘나가는 서비스이다.  
        데이터 센터가 있는 나라를 '리전'이라고 하는데 AWS는 클라우드 서비스 중 리전이 가장 많아서   
        세계 곳곳에서 빠른 속도의 서비스를 제공해준다.  

    2. CI/CD의 개념에 대해서 알기  
        - CI는 Continuous Integrarion, 형상관리로 계속 통합하는 것을 말한다.  
        CD는 Continuous Delivery, 소스가 실제 운영 서비스에 딜리버리 되는 것을 말한다.  
        즉, CI/CD는 소스 저장소와 배포 시스템을 통합하는 것이고 아키텍처의 변화로 작아진  
        어플리케이션들을 부담없이 자주 배포하기 위해 필요하다. 예시로 GitHub Action이 있다. 

    3. RDB에 대해서 알아보고, RDB와 NOSQL의 차이점에 대해서 알기  
        - RDB는 관계형 데이터베이스로 표의 형태로 데이터가 저장되어 수정이 어렵다.
        NOSQL은 JSON 형태로 데이터가 저장되어 변경에 용이해 정형화된 데이터보다  
        비정형화된 데이터를 저장하는 용도로 사용한다. 

    4. 동적페이지와 정적페이지가 무엇인지 알기(CSR,SSR)  
        - 정적 웹페이지는 서버에 저장되어 있는 그대로 HTML을 전송하고, 속도가 빠르고  
        서버 부담이 적다는 장점이 있지만, 서비스가 한정적이고 내용변경이 어렵다는 단점이 있다. 회사소개, 포트폴리오 웹페이지로 많이 사용된다.  
        동적 웹페이지는 요청 정보에 따라 HTML을 처리하여 전송하고, 상황에 맞게 변하는 모습을 보여주며  
        관리가 쉽다는 장점이 있지만, 보안에 취약하고 검색 엔진 최적화가 어렵다는 단점이 있다.  
        블로그, 게시판, 날씨정보 등에 많이 사용된다. 
        동적웹페이지는 자바스크립트에 데이터를 포함해서 보낸 후, 클라이언트 쪽에서 HTML을 완성하는  
        방법인 CSR(Client-side rendering) 방식과 서버 쪽에서 템플릿 HTML에 데이터를 끼워넣어  
        완성된 형태의 HTML을 보내주는 방법인 SSR(Server-side rendering) 방식이 있다.   
        이들을 복합적으로 사용해 클라이언트 쪽에서 Ajax 요청을 보내서 서버에서 데이터를 받아와 HTML을 완성하는 방법도 있다. 


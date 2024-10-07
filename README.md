👋


# 기술경력서
## 디플럭스씨앤씨
- LG CNS 기업 복지몰 관리 시스템 유지보수
- LG LED 마스크 Pra.L(프라엘) 매출 현황 리포트 엑셀 생성 Python 코드 유지보수
  ### 기업 복지몰 관리자웹 로그인 개선
  - Linux, Java, Spring Boot(ION ICE Platform), MySQL, Vue(Nuxt), JavaScript 
  - 참여인원 : 1명
  - 참여역할
    - 500 에러를 지정 에러 문구로 변경
## 아이티월드: [한국건설기술연구원 상세](한국건설기술연구원.md)
- 한국건설기술연구원 건설인허가 시스템 유지보수, 운영
- 쿼리로 데이터 수정, 업무 진행 단계 조정 민원 해결
- DB 데이터 개선
- Linux, Java, Servlet, Tibero, Tomcat, JavaScript 

  ### 법 개정으로 유저 정보 추가
    - 참여인원 : 1명
    - 참여역할
       - 인허가 시스템에 유저 정보 추가: 사업자구분, 사업자등록번호, 상호명
       
## 데이터얼라이언스
- IoT 관련 관리자 웹 콘솔 개발, 유지보수
- MSA 구조로 웹과 DB를 직접 연결하지 않고 데이터 접근은 DB와 연동한 API를 통해 수행
- Linux, AWS, Java, Spring/Spring Boot, RESTful API, Tomcat

    1. IoT 디바이스 관리 시스템 개발
    - OCF(사물 인터넷) 시스템을 관리하고 등록된 사물(스마트 가전제품 등)의 상태를 조회하는 관리자 시스템 개발
    - 참여인원 : 3명
    - 참여역할
        - DB와 연결된 RESTful API와 연동하여 데이터를 관리하는 웹 콘솔 개발
        - 시스템 설정 조회/수정, 디바이스 목록 조회/상세 조회

    2. IoT 디바이스, 게이트웨이 등의 관리 시스템 개발
    - LoRa(장거리 통신) 디바이스, 게이트웨이를 등록, 목록 조회, 상세 조회, 수정, 삭제할 수 있는 관리자 시스템 개발
    - 참여인원 : 3명
    - 참여역할
        - DB와 연결된 RESTful API와 연동하여 데이터를 관리하는 웹 콘솔 개발
        - 장거리 통신 디바이스, 게이트웨이 목록 조회, 등록, 수정, 삭제 기능 개발
        - 디바이스와 통신을 하며 보낼 데이터를 입력하여 전송, 조회, 삭제 기능 개발
        - 디바이스 실시간 데이터 통신 : MQTT 구독하여 화면에 로그처럼 계속 뿌려줌

    3. InfluxDB 연동 KAIA 데이터 그래프 모니터링 시스템 개발
    - 실시간 데이터를 InfluxDB에서 가져와 웹에 Grafana로 그래프로 보여줌, 디바이스/게이트웨이 정보를 조회
    - 참여인원 : 3명
    - 참여역할
	- DB와 연결된 RESTful API와 연동하여 데이터를 조회하는 웹 개발
         - InfluxDB와 연동한 Grafana 그래프 삽입

## 아이티빌리지

## 이젠솔루션
### 신세계I&C : 스타벅스 리워드 시스템 API 유지보수
- RESTful API 형식으로 요청에 대해 JSON 포맷 기반 응답
- 우수회원 선정, 블랙리스트 닉네임 마스킹
- Unix, Java, Spring, iBatis, Oracle, Jeus

    1. 삼성 스마트워치 Gear S3 연동 스타벅스 앱 API 추가 개발 
    - 기존 스타벅스 앱에서 사용하는 API를 Gear S3 전용으로 따로 새로운 서비스로 재구성  
    - 참여인원 : 2명
    - 참여역할
        - 로그인 : 가입된 회원정보로 인증하여 세션 아이디를 생성
        - 로그아웃 : 로그인한 사용자의 세션 정보를 삭제
        - 리워드 조회 : 회원등급에 따른 리워드 정보 반환
        - 카드 목록 조회 : 회원이 등록한 카드 목록을 반환
        - 카드 상세 조회 : 회원이 조회한 카드의 잔액, 바코드 URL 등 반환
        - 대표 카드 조회 : 대표 카드의 번호, 이미지 URL, 잔액, 카드 닉네임 등 반환
 
    2. e-Gift 거절하기 API 추가 개발
    - 개요 : 김영란법 제정으로 e-Gift가 발송된 문자와 이메일을 거절하는 기능 추가. 
    - 상세 기능 설명 : 
        - 거절가능 기간이 있으며(7일) 지나면 거절하기 불가.
        - 거절한 e-Gift는 보낸 사람 아이디에만 사용하거나 환불할 수 있다.
    - 참여인원 : 2명
    - 참여역할
        - 주문 상세 API : 거절여부 반환값(Y/N) 추가
        - 카드 등록 API : 거절여부가 Y이면 보낸사람 아이디에만 등록가능
        - 주문 취소 API : 거절여부가 Y면 취소 기간 내 주문 취소 가능

이젠솔루션: LGU+ 홈플러스 모바일 상품권 API, 관리자 웹 유지보수
- MMS 발송 시스템 개선, 관리자 페이지 수정, API 전송 항목 추가
- Unix, Java, JSP, Struts, iBatis, Oracle, Tomcat

    1. 보안취약점 개선
    - 참여인원 : 1명
    - 참여역할
      - 서버단에 비밀번호 체크 추가
      - 이전에 사용했던 비밀번호 재사용 금지 추가
      - 자신의 정보 변경 후 자동 로그아웃 및 로그인 페이지로 이동하도록 수정
      - 관리자가 사용자 정보 변경 시 관리자 인증 절차 추가
      - XSS에 대한 필터링과 차단
      - 디렉토리 인덱싱 차단
      - 4xx, 5xx 에러 발생에 따른 redirection 페이지 지정
      - 로그아웃 이후 이전 페이지로 이동이 가능하여 HTTP Response Header에 캐시 방지 설정
      - 인증정보(아이디/패스워드) RSA 암호화 전송

    2. 고객정보 암호화 개발
    - 참여인원 : 1명
    - 참여역할
       - 생년월일, 성별 7자리: AES256으로 암호화 
       - 비밀번호: SHA-512로 암호화




이젠솔루션: LGU+ 멤버십 API 유지보수
- 로그에 생년월일 결과값이 null로 나오던 것 수정
- 승인/조회 API에 할인율 조회 추가
- Unix, Java, Spring/Struts, iBatis, Jeus, webtob

이젠솔루션: LGU+ 인앱빌링 운영
- OpenSSL 보안취약점이 발견되어 상위버전으로 업데이트
- 보안취약점 조치: 디렉토리 인덱싱 비활성화로 서비스 코드 접근 차단, 서버 에러 발생에 따른 Redirection 페이지 지정
- Linux, Java, Spring, Altibase, Apache, Tomcat

## 쓰리에스인텍
- 외환은행 업무 프로세스 시스템 외국환 유지보수, 운영
- Linux, Java, JSP, Oracle, Miplatform, JavaScript
## 내외통신
- 뉴스 웹사이트 유지보수, 운영
- 다음 뷰와 XML로 뉴스기사 연동
- Linux, PHP, MySQL, HTML, CSS, JavaScript
<!--
**choimoonjung/choimoonjung** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

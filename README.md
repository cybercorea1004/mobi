# Mobi Framwwork 사용 가이드

## 프로젝트 개요
이 가이드는 (주)모비에서 사용하기위한 프레임웍의 라이브러리를 관리하기 위해 만든 프로젝트이며, <br>
공통 프레임웍팀에서 제공되는 API를 기반으로 사용할 수 있도록 가이드하고 표준화하는데 사용됩니다. <br><br>
주요 콤포넌트 : <br>

- com.emobi.emobi-common
(common util) : 공통으로 사용되는 util 및 interface 구성 <br>

- com.emobi.emobi-egov
(egovment framework application) : 전자 정부 프레임웍 컴포넌트 활용 구성<br>

- com.emobi.emobi-redis
(emobi-redis) : 비동기 토픽 교환을 통한 인터페이스 레파지토리 활용<br>

- com.emobi.emobi-mqtt
(emobi mqtt) : 동기 토픽 교환을 통한 인터페이스 레파지토리 활용 <br>

- com.emobi.emobi-socket
(socket) : 인터페이스 소켓 통신<br>

- com.emobi.emobi-rest
(emobi-rest) : Rest 통신<br>

- com.emobi.emobi-websocket
(emobi-websocket) : Websocket 통신<br>

- com.emobi.emobi-scheduler
(emobi-scheduler) : 다이나믹 스케쥴러를 통해 스케줄러의 생성 및 시작 / 정지 등을 관리한다. <br>

- com.emobi.emobi-nettyserver
(emobi netty server) : 비동기 인터페이스 서비스를 위한 Netty Server<br>

- com.emobi.emobi-netty
(emobi netty) : 비동기 인터페이스 서비스를 위한 Netty Client<br>

- com.emobi.emobi-mongo
(emobi-mongo) : MongoDB 데이터베이스<br>

- com.emobi.emobi-board
(emobi board) : 게시판 관리<br>

- com.emobi.emobi-ems-service : EMS 서비스 비지니스 예제<br>

- com.emobi.emobi-ems-mgmt
(emobi-ems-mgmt) : 관리자 서비스 예제<br>

- com.emobi.emobi-ems-user
(emobi-ems-user) : 사용자 서비스 예제<br>

- com.emobi.emobi-report
(emobi-report) : 보고서 관리<br>


- com.emobi.emobi-menu
(emobi menu) : 메뉴 관리<br>

- com.emobi.emobi-member
(emobi member) : 사용자 관리<br>

- com.emobi.emobi-auth
(emobi auth) : 사용자 권한 관리<br>

- com.emobi.emobi-email
(emobi email) : 이메일 발송 관리<br>

- com.emobi.emobi-sms
(emobi sms) : SMS 발송 관리<br>



# **Web Application Server(WAS)**

`Web Application Server` 는 인터넷 상에서 `HTTP`를 통해 사용자 컴퓨터나  장치에 Application을 수행해 주는 `소프트웨어 엔진`이다. WAS는 이러한 기능이 있습니다.

- 프로그램 실행 환경과 데이터베이스 접속 기능을 제공한다.

- 여러 개의 트랜잭션을 관리한다.

- 업무를 처리하는 비즈니스 로직을 수행한다.

대표적인 예시로는 `Zeus`, `Weblogic`, `Jboss` 등이 있지만. 저는 `Apache Tomcat`을 주로 쓰기 때문에
`Apache Tomcat`을 설명할 것입니다.



#### 용어 설명


`HTTP (HyperText Transfer Protocol)` : WWW 상에서 정보를 주고받을 수 있는 프로토콜 ( 통신 규약 )

`World Wide Web ( WWW, W3, Web )` - 인터넷에 연결된 컴퓨터들을 통해 사람들이 정보를 공유할 수 있는 공간

`Internet` - TCP/IP 라는 통신 프로토콜을 이용해 정보를 주고받는 컴퓨터 네트워크

`TCP/IP` - 인터넷에서 컴퓨터들이 정보를 주고받는데 쓰이는 통신규약 ( 프로토콜 )



#### WAS와 Web Server의 차이 

`Web Server`는 웹 브라우저(`Web Client`)에게 Contents를 제공하는 서버이고, 정적인 HTML이나 jpg,gif 등의 image를 http 프로토콜을 통해 웹 브라우저에게 제공합니다.   `WAS`는 Application을 동작할 수 있도록 지원하며, 현재는 `Serlvet, JSP, asp, php`등의 프로그램에도 이용되고 있습니ㅏㄷ.
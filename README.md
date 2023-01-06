"# handsUpChat" 
## 2023.1.06

stomp이용해보려다가 너무 안 되서 WebScocket만을 이용한 코드를 그대로 사용하였다.

참고 : https://learnote-dev.com/java/Spring-%EA%B2%8C%EC%8B%9C%ED%8C%90-API-%EB%A7%8C%EB%93%A4%EA%B8%B0-webSocket%EC%9C%BC%EB%A1%9C-%EC%B1%84%ED%8C%85%EC%84%9C%EB%B2%84-%EA%B5%AC%ED%98%84%ED%95%98%EA%B8%B0/

알게된 점 : http요청으로 채팅 구현을 구현하려면 주기적으로 요청을 해야하는 등 비용이 많이든다. 이를 해결하기 위해 websocket을 사용해, 연결을 끊기 전까지 유지하는 것이다.

STOMP 프로토콜은 WebSocket 위에서 동작하는 프로토콜로써 클라이언트와 서버가 전송할 메세지의 유형, 형식, 내용들을 정의하는 매커니즘이다.

# HTTP Network Basic

- TCP/IP
    - TCP/IP Model vs OSI 7 Layer
        - OSI 모델과는 달리 4개의 Layer로 구성 (7계층의 복잡성을 4계층으로 단순화시킨 모델)
        - Application Layer (Application Layer, Presentation Layer, Session Layer)
        - Transport Layer (Transport Layer)
        - Internet Layer (Network Layer)
        - Network Interface (Data Link Layer, Physical Layer)
    - TCP/IP vs UDP
        - 연결 지향적 vs 비연결 지향적
        - 순서 유지 vs 순서 비유지
        - 데이터 중복, 손실 없음 vs 데이터 중복, 손실 있음
        - 에러 발생 시 재전송 vs 에러 발생 시 재전송하지 않음
    - 3-Way Handshaking
        - Client-Server 연결 시 동작
    - 4-Way Handshaking
        - Client-Server 연결 해지 시 동작  
    - 공인 IP vs 사설 IP
        - 공인 IP는 전세계에서 유일
        - 사설 IP는 하나의 네트워크 안에서 유일

- MAC(Media Access Control)
    - 네트워크 카드 하드웨어에 부여되는 고유한 물리적 주소 (전세계적으로 유일)
    - ARP(Address Resolution Protocol)
        - IP를 MAC 주소로 변환하는 프로토콜

- DNS(Domain Name Server)
    - www.google.com과 같은 도메인을 IP로 변경해주는 서버
    - A Record
        - 도메인에 대한 IP 주소를 맵핑
    - CNAME(Canonical Name)
        - 도메인에 대한 도메인을 맵핑

- HTTP
    - HTTPS
        - SSL
        - TLS
    - HTTP/2.0
    - HTTP Header
    - HTTP Method
    - HTTP Status Code
    - HTTP Stateless
        - Cookie

- Proxy vs Gateway vs Tunnel

- AJAX

- WebSocket

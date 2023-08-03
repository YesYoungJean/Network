# 네트워크에 대해 알아보자!!

## 네트워크(Network)란?
    - 정보를 공유할 수 있도록 함께 연결된 컴퓨터 시스템
    - 노드와 링크가 서로 연결되어 있으며, 리소스를 공유하는 집합
     * 노드: 서버, 라우터, 스위치 등 네트워크 장치
     * 링크(엣지): 유선 또는 무선과 같은 연결 매채(와이파이/LAN)
![image](https://github.com/YesYoungJean/Network/assets/107979338/801340c5-bd81-4eb4-83c0-ac26ace40a6e)
<br/>
<br/>

## 네트워크 용어 및 구
### 트래픽 (Traffic)
    - 특정 시점에 링크 내의 흐르는 데이터의 양을 지칭
      * 트래픽 증가 == 링크 내 데이터 증가
      * 처리량 증가 == 처리되는 트래픽 증가
      * 단위: bps(bits per second)
      
### 처리량 (Throughput)
    - 링크 내에서 성공적으로 전달된 데이터의 양 (처리한 트래픽의 양)
    - 많은 트래픽을 처리함 == 많은 처리량을 가짐
    - 처리량은 다수의 사용자가 접속할 때마다 커지는 트래픽, 네트워크 장치 간 대역폭, 에러, 하드웨어 스펙 등의 영향을 받음

### RTT (Round Trip Time: 왕복 지연시간)
    - 신호를 전송하고 해당 신호의 수신 확인에 걸린 시간을 더한 값으로, 메시지가 두 장치를 왕복하는데 걸린 시간
<br/>
<br/>
### 네트워크 기준 (Network Criteria)
    - 네트워크 필수 충족 기준
    * 성능(Performance) : delay, throughput 등등 고려
    * 신뢰성(Reliability)
    * 보안 (Security)

### 네트워크 물리적 구조
    - (a) 1:1 통신 (Point to Point)
    - (b) 1:N 통신 (MultiPoint)
![image](https://github.com/YesYoungJean/Network/assets/107979338/26534714-1b0e-47c2-bc54-4be72b80615e)




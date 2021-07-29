# MQTT-Project-Monitoring-App
<MQTT 기반 메시지 서버의 성능 모니터링 시스템>의 모니터링 앱 파트입니다.

전체 프로젝트 배경과 설명은 첨부파일-최종 보고서에서 확인 가능합니다.


## 1. 프로젝트 전체 구조
<img src = "https://user-images.githubusercontent.com/38847724/127315703-15176e0d-dbb7-4b4c-a5c6-508073f110a0.png" width="90%" height="90%">


## 2. 그 중 Test MQTT Message Platform(Monitoring App) 파트
<img src = "https://user-images.githubusercontent.com/38847724/127519243-d3195a11-1aae-4bb6-8640-ff8c2fdbe78a.png" width="90%" height="90%">

## 3. 모니터링 항목
### Target MQTT Message Server의 성능 정보
- CPU 사용량
- Memory 사용량
- Network I/O
- Process Information

### Target MQTT Message Server에서 처리되는 메시지 트래픽 정보
- 현재 연결된 클라이언트 수
- 최근 연결된 클라이언트
- 가장 오래 연결된 클라이언트
- 메시지 수를 기반으로 최대 처리량/최소 처리량을 갖는 클라이언트
- 토픽 별 가입자 리스트와 메시지 송/수신 횟수, 처리량
- 클라이언트 별 처리량

⇒위 정보들을 모니터링 웹 서버의 데이터베이스에 저장합니다.

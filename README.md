# 앱 구조

## 시작

### command

```bash
docker compose up -d
```

### endpoints

1. app
   1. consumer: 3001
   1. producer: 3002
1. kafka - ui: 9000
1. grafana: 3003
1. prometheus: 9090

### grafana dashboard
1. node
    - https://grafana.com/grafana/dashboards/11159-nodejs-application-dashboard/
1. kafka
    - https://grafana.com/grafana/dashboards/7589-kafka-exporter-overview/

# 미션

## kafka JS를 이용해서 초당 1만개 produce / consume에 성공하기

### 측정 방법

- grafana dashboard의 초당 처리량 확인
  - 사진으로 인증

### 제한 사항
- docker desktop 설정은 메모리 16GB까지 허용
- 이외 제한 없음


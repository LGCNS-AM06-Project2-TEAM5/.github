# 5조 · 혜자 MSA

LG CNS AM INSPIRE CAMP 6기 미니프로젝트 2 · 2026-10-30 ~ 11-05

청년 주거 정책 추천 서비스 「혜자」를 마이크로서비스 4개로 나누고, OpenFeign·Kafka로 연결하고, Docker Compose로 AWS EC2에 배포했습니다.

## 저장소

| 저장소 | 내용 |
|---|---|
| [hyeja-msa](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa) | 2차 작업 저장소. Eureka·Gateway·Config, 서비스 4개(user·policy·engagement·recommendation), Docker Compose, CI/CD, 산출물 문서 |
| [hyeja-config](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-config) | Spring Cloud Config Server 설정 저장소 |
| [hyeja-backend](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-backend) | 1차 혜자 백엔드 코드. 서비스로 나눈 코드의 출발점 |
| [hyeja-frontend](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-frontend) | 혜자 프런트엔드. Gateway 연결, 관리자 운영 화면 |

## 시작하기

1. [hyeja-msa README](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa#readme)와 [협업 규칙](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/blob/develop/docs/협업규칙.md)을 읽습니다.
2. 작업은 `develop`에서 브랜치를 만들고 `develop`으로 PR을 보냅니다.

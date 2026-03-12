# 코인 국내외 거래소 차익 거래 프로그램 개발 — 제안 분석 로그

> 생성일: 2026-03-11
> 공고 URL: https://www.wishket.com/project/153117/

## 1. 공고 파싱 결과

```yaml
job:
  title: "코인 국내외 거래소 차익 거래 프로그램 개발"
  category: "개발 > 웹PC 프로그램 > 가상화폐·거래소"
  budget_range: "2,500,000원"
  duration: "14일"
  tech_stack: [Python, Websocket, asyncio, 멀티쓰레드]
  description: "국내/해외 거래소 간 현물 아비트리지 모니터링 프로그램 구축"
  requirements:
    - "Websocket 기반 실시간 호가 수집 (빗썸, 업비트, Gate, Binance, Bybit)"
    - "스프레드 계산 및 필터링 (사용자 설정 최소 수익률)"
    - "입출금 상태 필터 (출금 중지 코인 자동 필터링)"
    - "네트워크 정보 표시 (거래소별 동일 코인 네트워크 종류)"
    - "Gate.io 전용 대출 가능 여부 조회"
    - "알림 기능 (소리 알림 + 텔레그램 메시지)"
  client_questions: []
  deadline: "2026년 03월 17일"
  job_post_url: "https://www.wishket.com/project/153117/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음.

## 3. 실현 가능성 분석 (내부용)

- **프로젝트 유형**: API + 웹 프론트 → "가능" (+10% 버퍼)
- **기본 공수**: 18 M/D
  - 기획/설계: 2 M/D
  - Websocket 어댑터 프레임워크 + 5개 거래소: 6 M/D
  - 스프레드 계산 엔진: 1.5 M/D
  - 입출금 상태 필터: 1.5 M/D
  - 네트워크 정보 표시: 1 M/D
  - Gate.io 대출 조회: 0.5 M/D
  - 알림 시스템 (텔레그램 + 소리): 1.5 M/D
  - 설정 관리 + asyncio 아키텍처: 2 M/D
  - QA/테스트/문서: 2 M/D
- **AI 반영 공수**: 9.0 M/D (가중 평균 ~50% 절감)
- **+10% 버퍼**: 9.9 M/D ≈ 10 M/D
- **달력 일수**: 10 M/D × (7/5) = 14 달력일
- **클라이언트 예상 기간 vs 산정 기간**: 14일 vs 14일 — 일치
- **판정**: 클라이언트 기간 그대로 사용 가능

## 4. 포트폴리오 매칭

| 순위 | 프로젝트 | 매칭 점수 | 근거 |
|------|---------|----------|------|
| 1 | P2P Funding | 85/100 | Python/Django 금융 플랫폼, 15+ 외부 API 연동, 금융 계산 엔진, 자동화 처리 |
| 2 | Life3 | 80/100 | Web3/DeFi 토큰 스왑, 크립토 도메인 전문성, 이벤트 드리븐 아키텍처, 실시간 처리 |
| 3 | NFT-DeFi | 70/100 | 블록체인/DeFi, 토큰 이코노미, 온체인/오프체인 브릿지, 3개월 빠른 딜리버리 |

## 5. 최종 제안 요약

- **지원 금액**: 2,250,000원 (VAT 별도) — 클라이언트 예상 금액 2,500,000원의 90%
- **지원 기간**: 14일
- **핵심 제안 포인트**:
  1. asyncio + 어댑터 패턴으로 5개 거래소 Websocket 안정적 병렬 처리
  2. Python 금융 플랫폼(P2P) 및 Web3/DeFi(Life3) 유사 프로젝트 경험
  3. 단순 가격 비교가 아닌 입출금 상태 + 네트워크 호환성까지 종합 판단 시스템

## 6. 최종 산출물

### 제안 사이트
- URL: https://proposal-crypto-arb-monitor.pages.dev/
- 저장소: https://github.com/Blue-Verse/proposal-crypto-arb-monitor

### 위시켓 폼 입력값

**지원 금액**: 2,250,000원

**지원 기간**: 14일

**클라이언트 질문 답변**: (질문 없음)

**지원 내용**:

안녕하세요, 블루버스입니다.

**코인 국내외 거래소 차익 거래 프로그램 개발** 프로젝트에 지원합니다.

**왜 블루버스인가?**
- Python 기반 금융 플랫폼(P2P Funding)에서 15개 이상 외부 API를 실시간 연동한 경험이 있습니다. 5개 거래소 Websocket 병렬 처리에 직접 적용 가능합니다.
- Web3/DeFi 프로젝트(Life3)에서 토큰 스왑·이벤트 드리븐 아키텍처를 구축했습니다. 크립토 도메인과 실시간 데이터 처리 모두에 깊은 이해를 갖추고 있습니다.
- NFT-DeFi 프로젝트에서 온체인/오프체인 브릿지 및 빠른 딜리버리(3개월) 경험이 있어 14일 일정 내 안정적 납품이 가능합니다.

**핵심 기술 접근**
1. asyncio + Adapter Pattern으로 빗썸·업비트·Gate·Binance·Bybit 5개 거래소 Websocket을 안정적으로 병렬 수집
2. 단순 가격 비교가 아닌, 입출금 상태 + 네트워크 호환성까지 종합 판단하는 실전형 아비트리지 모니터링
3. 텔레그램 + 소리 알림으로 수익률 기준 초과 시 즉각 알림

상세 제안서를 준비했습니다:
https://proposal-crypto-arb-monitor.pages.dev/

**관련 포트폴리오 추천**:
1. P2P Funding (매칭 85/100) — https://www.wishket.com/partners/p/blueverse1/portfolio/
2. Life3 (매칭 80/100) — https://www.wishket.com/partners/p/blueverse1/portfolio/
3. NFT-DeFi (매칭 70/100) — https://www.wishket.com/partners/p/blueverse1/portfolio/

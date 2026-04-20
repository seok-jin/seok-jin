<h1 align="center">Lim Seokjin (임석진)</h1>
<h3 align="center">Data Architect · BI Engineer</h3>

<p align="center">
  <a href="mailto:hopesukjin@gmail.com"><img src="https://img.shields.io/badge/Email-hopesukjin%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/da-lsj/"><img src="https://img.shields.io/badge/LinkedIn-da--lsj-blue?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Experience-7%2B%20years-green?style=flat-square" />
</p>

---

## About Me

7년 이상 **데이터 거버넌스 · 품질 · 표준화** 체계 구축을 주도해 온 Data Architect 입니다.
최근에는 **BI 엔지니어링**과 **GenAI 기반 데이터 서비스** 쪽으로 영역을 넓혀, 전사 데이터를 의사결정에 바로 쓰이는 지표·대시보드·AI 서비스로 연결하는 일에 집중하고 있습니다.

- 대기업 · 공공 프로젝트에서 **전사 표준화 / 품질 진단 / 거버넌스 시스템** 운영 경험
- PowerBI 기반 **품질 현황 대시보드** 기획 및 개발 (GS Caltex 전사 지표)
- Airflow · Python 기반 **데이터 파이프라인** 설계 및 운영
- **GenAI × 거버넌스** 통합 서비스 개발 (RAG 기반 표준 가이드 Q&A)

---


## Tech Stack

<p>
  <img src="https://img.shields.io/badge/SQL-Native-003B57?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Data%20Modeling-Native-0078D4?style=flat-square" />
  <img src="https://img.shields.io/badge/Data%20Quality-Native-4CAF50?style=flat-square" />
  <img src="https://img.shields.io/badge/PowerBI-Intermediate-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-Intermediate-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Airflow-Intermediate-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-SAA-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/GenAI-Basic-FF6F00?style=flat-square" />
</p>

**Data Platform**: DA#, DQ#, META#, Erwin  
**Database**: Oracle, MSSQL, PostgreSQL, SQLite  
**BI / Viz**: PowerBI, Streamlit  
**Language**: SQL, Python

---

## Featured Projects

### [coin_quant](./) - End-to-End 데이터 파이프라인 & 실시간 BI 대시보드
> 암호화폐 자동매매 시스템을 **BI 엔지니어 관점**에서 설계. 데이터 수집 → 모델링 → 분석 → 시각화의 전체 스택을 개인 프로젝트로 구현.

- **11개 테이블 SQLite 스키마** 설계 (실시간 파라미터 관리 포함)
- **30분 주기 ETL 파이프라인**: OHLCV 수집 → 15개 기술지표 계산 → 저장
- **Streamlit BI 대시보드**: 실시간 포지션 · 손익 · 지표 현황 모니터링
- **AWS EC2 24/7 운영**: systemd 기반 무중단 서비스

`Python` `SQLite` `Streamlit` `Pandas` `AWS EC2`

### [fin_research](./) - 멀티 자산 금융 데이터 분석 플랫폼
> 한국/미국 주식 + 매크로 지표를 통합 수집해 상관관계 · 시장 레짐 · 백테스팅을 자동화.

- **멀티 소스 ETL**: pykrx(한국주식) / yfinance(미국) / FRED(매크로) → Parquet 캐시
- **정량 분석**: 자산간 상관관계, 시장 레짐 탐지, Sharpe/VaR 리스크 지표
- **Streamlit 대시보드**: 시장 개요 · 상관관계 히트맵 · 백테스트 결과

`Python` `SQLite` `Parquet` `Streamlit` `pykrx` `yfinance`

---

## Other Claude Code Projects

**Claude Code** 를 활용해 직접 설계·구현한 사이드 프로젝트들입니다.
AI 에이전트 오케스트레이션 · 자동화 파이프라인 · 웹서비스 등 다양한 도메인을 다루며 빠른 프로토타이핑 역량을 보여줍니다.

### AI Agent · Orchestration

| 프로젝트 | 설명 | Stack |
|---|---|---|
| **discord-multi-agent** | Discord 슬래시 명령으로 개발 작업을 투입하면 Planner / Coder / Reviewer / Tester 4개 AI 에이전트가 협력해 완수하는 멀티에이전트 시스템 | `Python` `Discord.py` `Claude API` |
| **tiktok_factory** | Gemini CLI(리서치) + Claude Code CLI(스크립팅) + matplotlib/FFmpeg 렌더링을 결합한 숏폼 영상 자동 생산 파이프라인 | `Python` `Multi-LLM` `FFmpeg` `edge-tts` |

### Automation · Data Pipeline

| 프로젝트 | 설명 | Stack |
|---|---|---|
| **product-automation** | 도매 사이트 크롤링 → 트렌드/수요 분석 → 쿠팡/네이버 자동 등록까지의 이커머스 데이터 파이프라인 (FastAPI + Celery 비동기 워크플로우) | `FastAPI` `Celery` `SQLAlchemy` `Crawler` |
| **obsidian_brain** | 텔레그램 메시지를 Gemini가 의도 분석 후 Google Drive의 Obsidian 볼트에 자동 분류·저장하는 개인 지식관리 봇 | `Python` `Telegram` `Gemini` `GDrive API` |

### Web Service

| 프로젝트 | 설명 | Stack |
|---|---|---|
| **korean-name-generator** | 영어권 사용자를 위한 한글 이름 생성 웹앱 (의미·한자·발음 동시 제시) | `Next.js` `TypeScript` `React` |
| **saju-gunghap** | 사주/궁합 분석 + 길한 방위·색 추천 웹서비스 | `Next.js` `TypeScript` |

---

## Certifications

- **AWS Certified Solutions Architect – Associate** (2024.02)
- **ADsP** 데이터분석 준전문가 (2020.07)
- **정보처리기사** (2018.11)
- **SQLD** SQL 개발자 (2017.10)

---

## Contact

- **Email**: hopesukjin@gmail.com
- **LinkedIn**: [linkedin.com/in/da-lsj](https://www.linkedin.com/in/da-lsj/)
- **Location**: 경기도 용인시

> 데이터 거버넌스 · BI · GenAI 관련 협업 제안은 언제든지 환영합니다.

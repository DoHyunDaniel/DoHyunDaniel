<h1 align="center">Hi, I'm Daniel Kim 👋</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Backend%20Developer-Java%20%7C%20Python-blue?style=for-the-badge&logo=java&logoColor=white" alt="Backend Developer">
  <img src="https://img.shields.io/badge/Specialization-Real--time%20Services%20%7C%20LLM%20Chatbots%20%7C%20MSA-green?style=for-the-badge" alt="Specialization">
</p>

<p align="center">
  실시간 서비스 & 인증/보안 · LLM 기반 대화형 챗봇 · MSA & 모니터링 · Redis & OAuth2.0 경험 보유
</p>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DoHyunDaniel&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages">
</div>

---

## 💼 Featured Projects

### 💬 DoranDoran – Multi-Agent LLM Chatbot (MSA 기반 실서비스)
> **멀티 에이전트 LLM 기반 영어 표현 교정 & 학습 챗봇 서비스**  
> Java Spring Boot 3.x · Spring Cloud Gateway · PostgreSQL 17 · Redis 7 · OpenAI · Docker · AWS EC2

**핵심 기능:**
- 🧠 **Multi-Agent LLM Orchestration**  
  - Intimacy / Vocabulary / Conversation / Translation 에이전트 분리  
  - 병렬 + 순차 처리를 조합한 멀티 에이전트 구조
- 💬 **실시간 대화 경험**  
  - OpenAI Streaming API + **SSE 기반 스트리밍 응답**  
  - 대화, 교정, 단어 추천, 번역이 순차적으로 UI에 표시
- 🧾 **표현 보관함 & 학습 히스토리**  
  - 마음에 드는 표현/문장을 저장하고 재학습  
  - 친밀도(progress) 및 교정 기록 관리
- 🧱 **MSA + 멀티 스키마 DB 설계**  
  - Gateway / Auth / User / Chat / Store / Batch 서비스 분리  
  - PostgreSQL 단일 인스턴스 + `user/auth/chat/store/billing` 스키마 구조
- 🔐 **보안 & 운영**  
  - JWT 기반 인증, IP 블랙리스트 필터  
  - Prometheus + Grafana + Loki + Alertmanager 기반 모니터링  
  - DB 커넥션 풀/메모리 이슈 트러블슈팅 및 재발 방지

**기술 스택:**  
Java 21 · Spring Boot 3.3 · Spring Cloud Gateway · Spring Security · JPA  
PostgreSQL 17 · Redis 7 · Docker · Nginx · AWS EC2  
Prometheus · Grafana · Loki · Alertmanager · OpenAI API · React + TypeScript (FE 협업)

---

### 🔍 [YT2 Search System](https://github.com/DoHyunDaniel/yt2_search_project)
> **7가지 검색 알고리즘을 활용한 YouTube 데이터 검색 플랫폼**  
> Python · FastAPI · PostgreSQL · OpenSearch · React · AI/ML

**핵심 기능:**
- 🔎 **7가지 검색 알고리즘**  
  - 기본 검색, TF-IDF, 가중치 기반, BM25, 하이브리드, 의미 기반, 감정 분석 검색
- 📈 **AI 기반 통계 분석**  
  - 인기 비디오/채널, 카테고리별 트렌드, 감정 분석 기반 인사이트
- 🎯 **AI 추천 시스템**  
  - 콘텐츠 기반, 인기도 기반, 트렌드 기반 추천 로직 구현
- ⚡ **실시간 검색 UX**  
  - 800ms 디바운싱 & 검색 결과 캐싱  
  - YouTube API 자동 크롤링 및 메타데이터 적재
- 🎨 **반응형 UI/UX**  
  - Material Design 기반 대시보드형 인터페이스

**기술 스택:**  
Python 3.11 · FastAPI · PostgreSQL · OpenSearch · Redis  
React 18 · TypeScript · Docker · scikit-learn

---

### 💰 [MoneyBuddy](https://github.com/MoneyBuddyTeam/BE)
> **실시간 소비 상담 & 소비습관 개선 플랫폼**  
> Java · Spring Boot · Redis · WebSocket · OAuth2

**핵심 기능:**
- 🔐 **JWT + OAuth2 인증 시스템**
- 📸 **AWS S3 이미지 업로드**
- 💬 **Redis Pub/Sub & WebSocket** 기반 실시간 채팅
- 💳 **포인트 기반 결제/정산 시스템**
- 👨‍💼 **관리자 대시보드 & 상담 관리 기능**

**기술 스택:**  
Java 17 · Spring Boot · Spring Security · JPA  
MySQL · Redis · Docker · AWS EC2/S3

---

### 💬 [MoneyTalk](https://github.com/DoHyunDaniel/moneytalk)
> **중고거래 & 가계부 챗봇 플랫폼**  
> Java · Spring Boot · WebSocket · OAuth2

**핵심 기능:**
- 🔐 **JWT + OAuth2 인증**
- 📸 **AWS S3 이미지 업로드**
- 💬 **Redis Pub/Sub & WebSocket** 실시간 채팅
- ⭐ **리뷰 & 평점 시스템**

**기술 스택:**  
Java 17 · Spring Boot · Spring Security · JPA  
MySQL · Redis · Docker · AWS EC2/S3

---

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-green?style=flat-square&logo=spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.1xx+-green?style=flat-square&logo=fastapi&logoColor=white)

### Database & Cache
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-blue?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7.x-red?style=flat-square&logo=redis&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-2.x-orange?style=flat-square&logo=opensearch&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20S3-orange?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-24.x-blue?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI/CD-blue?style=flat-square&logo=github-actions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Proxy%20%7C%20SSL-brightgreen?style=flat-square&logo=nginx&logoColor=white)

### AI/ML & Security
![OpenAI](https://img.shields.io/badge/OpenAI-API-grey?style=flat-square&logo=openai&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red?style=flat-square&logo=pytorch&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-JWT-green?style=flat-square&logo=oauth&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Authorization-purple?style=flat-square&logo=json-web-tokens&logoColor=white)

---

## 📚 Certificates & Achievements

<div align="center">
  <img src="https://img.shields.io/badge/정보처리기사-Engineer%20Information%20Processing-blue?style=for-the-badge" alt="정보처리기사">
  <img src="https://img.shields.io/badge/SQLD-SQL%20Developer-orange?style=for-the-badge" alt="SQLD">
  <img src="https://img.shields.io/badge/ADsP-Data%20Analysis%20Professional-purple?style=for-the-badge" alt="ADsP">
</div>

---

## 📝 Blog & Contact

<div align="center">
  <a href="https://velog.io/@kdhdaniel0506">
    <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white" alt="Velog">
  </a>
  <a href="mailto:kdhdaniel0506@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/DoHyunDaniel">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="Footer">
</div>

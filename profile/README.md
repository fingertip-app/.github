<div align="center">

# 👋 장인과 하루

### RAG 기반 전통문화 체험 정보 및 AI 해설 서비스

전통문화 데이터를 AI로 이해하고,  
국가 인증 장인의 체험까지 연결하는 서비스입니다.

</div>

---

## 📌 About

장인과 하루는 여러 출처에 분산된 전통문화 데이터를 활용하여  
사용자가 관련 정보를 쉽게 탐색하고 AI 기반 해설을 받을 수 있도록 개발한 서비스입니다.

사용자의 질문과 관련된 문화유산 데이터를 벡터 검색으로 조회하고,
검색 결과를 기반으로 LLM이 답변을 생성하는 RAG 구조를 적용했습니다.

---

## 🏗 Architecture

사용자 질문  
→ OpenAI Embedding  
→ PostgreSQL / pgvector Vector Search  
→ 관련 문화유산 데이터 검색  
→ Context 구성  
→ OpenAI API  
→ AI 해설 생성

---

## 🛠 Tech Stack

### Backend
Python · FastAPI · SQLAlchemy · Alembic

### AI / RAG
OpenAI API · Embedding · RAG · pgvector

### Database
PostgreSQL · pgvector

### Async / Infra
Redis · Celery · Docker · AWS EC2

---

## ✨ Key Features

- 🔎 문화유산 데이터 기반 Vector Search
- 🤖 RAG 기반 AI 전통문화 해설
- 🧠 OpenAI Embedding 기반 유사도 검색
- 🔐 내부 AI API 인증 및 예외 처리
- ⚡ Redis / Celery 기반 비동기 처리 환경
- 🗄 SQLAlchemy / Alembic 기반 데이터 모델 및 마이그레이션

---

## 📂 Repositories

| Repository | Description |
|---|---|
| Backend | FastAPI 기반 백엔드 및 AI API |
| Frontend | 사용자 서비스 UI |
| AI / Data | RAG 및 문화유산 데이터 처리 |

---

## 👥 Team

| Role | Responsibility |
|---|---|
| Backend / AI | FastAPI, RAG, Vector Search |
| Frontend | UI / UX 및 API 연동 |
| Data | 문화유산 데이터 수집 및 전처리 |

---

<div align="center">

### 장인과 하루

AI로 전통문화를 이해하고, 실제 체험으로 연결합니다.

</div>

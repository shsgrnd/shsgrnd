# Hi there 👋  
## 저는 AI 기능을 실제 서비스 흐름으로 연결하는 개발자, 신형섭입니다.

섬유 연구에서 시작해 AI 서비스 개발로 확장해 온 경험을 가지고 있습니다.  
연구 과정에서 익힌 **가설 설정 → 실험 → 검증**의 태도를 바탕으로,  
지금은 모델을 단순히 학습시키는 것에 그치지 않고  
**서비스 안에서 안정적으로 동작하는 AI 시스템**을 만드는 데 집중하고 있습니다.

---

## 🔎 About Me

- 🎓 한양대학교 의류학과 학사 / 의류학과 석사
- 🧪 스마트텍스타일, 웨어러블 센서, 마찰전기 나노발전기 연구 경험
- 💻 삼성 청년 SW·AI 아카데미 14기 Python Track
- 🤖 AI 모델 평가, STT, 추천 시스템, LLM 파인튜닝, AI 서비스 인프라에 관심
- 🧩 문제를 구조적으로 분석하고, 실제 사용자 흐름에 맞게 기능을 완성하는 것을 중요하게 생각합니다.

---

## 🛠 Tech Stack

### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![ScikitLearn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

### Backend / API
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQLfor-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### Frontend / Extension
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![VSCode](https://img.shields.io/badge/VS_Code_Extension-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

### Infra
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 🚀 Projects

### 🐱 GitCat  
**생성형 AI 코딩 환경에서의 안전한 작업 관리 및 스마트 병합 VS Code Extension**

- VS Code Extension 기반 AI 작업 관리 도구 개발
- 로컬 스냅샷 저장 / 복구 구조 설계
- SFT / DPO 학습 및 Base-SFT-DPO 평가 비교
- GGUF 변환 및 로컬 LLM 추론 연동
- VSIX 패키징 및 배포 구조 최적화

**Keywords**  
`LLM Fine-tuning` `SFT` `DPO` `VS Code Extension` `Local LLM` `SQLite` `GGUF`

---

### 🏠 NUVIS  
**스마트홈 로봇 추천 AI 및 STT 명령 파이프라인**

- 사용자 생활 패턴 기반 IoT 기기 추천 AI 설계
- Whisper 기반 스마트홈 명령 STT 파인튜닝
- 후처리 파서 설계로 실제 명령 변환 안정성 개선
- AI 서버와 백엔드 간 Stateless API 구조 설계
- timeout, fallback, payload 제한 등 예외 처리 기준 정리

**Keywords**  
`Whisper` `STT` `FastAPI` `Recommendation AI` `PyTorch` `Scikit-learn`

---

### 👕 AirDresser  
**등록 기반 AI 의류 케어 보조 서비스**

- 의류 등록 시점에 라벨 OCR 정보를 저장하고, 판단 시점에는 외형 사진만으로 케어 가능 여부 판단
- `AUTO / CONFIRM / BLOCK / REGISTER_FIRST` 판단 흐름 설계
- OCR 오염 문자열 보정 및 규칙 기반 라벨 해석 구조 구현
- 이미지 유사도 기반 등록 의류 매칭 정책 설계
- Vue 3, FastAPI, PostgreSQL 기반 풀스택 구현

**Keywords**  
`Vue 3` `FastAPI` `OCR Correction` `Image Similarity` `PostgreSQL` `Docker Compose`

---

### 🎙 Speaky  
**AI 기반 실시간 페르소나 리마스터링 서비스**

- WebRTC 기반 실시간 스트리밍 서비스 개발
- 연결 상태 머신 기반 UX 설계
- 디버그 패널 및 시그널링 관측 도구 구현
- 세션 유지, 장치 제어, 오류 복구 흐름 개선

**Keywords**  
`WebRTC` `React` `TypeScript` `Spring Boot` `WebSocket`

---

## 📌 What I Focus On

```text
AI 모델을 만드는 것보다,
그 모델이 실제 서비스 안에서 안정적으로 동작하도록 연결하는 일에 관심이 있습니다.
```

- 모델 평가와 실패 원인 분석
- AI 서버와 서비스 백엔드 간 책임 분리
- 사용자 흐름을 고려한 fallback UX
- 실험 결과를 재현 가능한 문서와 지표로 남기는 개발 방식
- 기능 구현 이후의 패키징, 배포, 운영 가능성 점검

---

## 📫 Contact

- Email: gudtjq08@gmail.com
- GitHub: [github.com/shsgrnd](https://github.com/shsgrnd)

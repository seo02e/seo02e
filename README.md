<img src="https://capsule-render.vercel.app/api?type=rect&color=0:667eea,100:764ba2&height=240&section=header&text=Junseo%20Kim&fontSize=55&fontAlignY=40&animation=fadeIn&fontColor=FFFFFF&desc=Backend%20Engineer%20%7C%20FastAPI&descAlignY=65&descSize=18&descColor=E0E0E0"/>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?color=6464FC&size=28&center=true&vCenter=true&width=700&lines=Building+AI-powered+services;Backend+%7C+API+%7C+Data+Processing"/>
</div>





### 🚀 FastAPI 기반 백엔드 개발자를 목표로 성장 중입니다.


</div>

---

## 🧑‍💻 About Me
- 🎓 한림대학교 졸업
- 🔥 FastAPI 기반 백엔드 개발 집중
- 🧠 데이터 처리 및 API 설계에 관심
- 📈 AI + Backend 결합 서비스 개발 목표

---

## 🚀 Projects

### 🧠 HR Risk Dashboard
> 조직 데이터를 기반으로 직원 리스크를 분석하는 백엔드 시스템

**📌 My Role (Backend)**
- FastAPI 기반 API 서버 설계 및 구현
- MariaDB 데이터 모델링 및 SQL 분석 쿼리 작성
- CSV 데이터 → DB 적재 파이프라인 구축

**📌 Features**
- 평균 연봉, 조직 건강도 등 지표 분석 API 제공
- 데이터 기반 리스크 분석 결과 제공

👉 https://github.com/ghjkl90/Mini_Team2_Home_Project

---

### 🔍 Youth Policy Chatbot (RAG 기반)
> 사용자 조건에 맞는 청년 지원 정책을 찾아주는 챗봇 서비스

**📌 My Role (Backend)**
- FastAPI 기반 챗봇 API 서버 설계 및 구현
- Redis 기반 세션 관리 및 대화 상태 저장
- 사용자 입력 → AI 모듈 → 응답 흐름 orchestration 구현
- AI 모듈(parser, retriever, rag)과의 인터페이스 구현

**📌 My Role (Frontend)**
- API 테스트 및 기능 검증을 위한 간단한 UI 구현
- axios 기반 API 연동 및 데이터 시각화
- 사용자 입력 → 결과 출력 흐름 구성

**📌 System Flow**
1. 사용자 입력 수신
2. 파싱 모듈로 조건 추출
3. 조건 기반 정책 필터링
4. RAG 모듈을 통한 응답 생성
5. 결과 반환 및 세션 저장

**📌 Tech**
- FastAPI / Redis / REST API
- RAG 구조 기반 서비스 연동

👉 https://github.com/seo02e/advanced_project

---
### 🎨 AI Trademark Logo Generator
> 자연어·이미지 입력을 기반으로 상표·로고를 생성하고, 기존 상표와의 유사도를 분석해 도용 가능성을 판별하는 AI 서비스

## 📌 My Role (Backend)

- FastAPI 기반 로고 생성 API 설계 및 구현
- 사용자 자연어 입력 검증 및 프롬프트 처리 흐름 구현
- LLM을 활용한 한국어 입력 → 이미지 생성용 영문 프롬프트 변환 연동
- 이미지 생성 API(DALL-E 3 또는 Stable Diffusion) 연동 구조 설계
- 생성된 로고 이미지 결과 저장 및 응답 처리
- 관리자 권한 기반 상표·로고 삭제 기능 구현
- 삭제 사유, 삭제 시각, 관리자 ID를 기록하는 Soft Delete 구조 설계

## 📌 Main Features

### FR-05 자연어 기반 로고 생성

- 사용자가 입력한 자연어 프롬프트를 기반으로 로고 생성
- 한국어/영어 입력 지원
- 입력 프롬프트 최대 500자 제한
- 한국어 입력 시 LLM을 통해 이미지 생성용 영문 프롬프트로 변환
- 1024×1024 PNG 형식의 로고 이미지 생성
- 1회 요청당 최대 4개 변형 이미지 생성

### FR-38 상표·로고 삭제 기능

- 관리자 권한 사용자만 상표·로고 삭제 가능
- 단건 삭제 및 다건 일괄 삭제 지원
- 삭제 사유 입력 필수
- 삭제된 데이터는 Soft Delete 방식으로 처리
- 30일 보관 후 영구 삭제 가능하도록 설계
- 관리자 삭제 로그 기록

## 📌 System Flow

사용자 자연어 입력 수신  
↓  
입력값 검증 및 금칙어 확인  
↓  
LLM을 통한 영문 프롬프트 변환  
↓  
이미지 생성 API 호출  
↓  
생성된 로고 이미지 저장  
↓  
생성 결과 DB 저장  
↓  
유사도 검사 결과 연동  
↓  
결과 반환 및 법적 고지 표시  

## 📌 Admin Flow

관리자 로그인  
↓  
상표·로고 목록 조회  
↓  
삭제 대상 선택  
↓  
삭제 사유 입력  
↓  
Soft Delete 처리  
↓  
관리자 로그 저장  
↓  
30일 이후 영구 삭제 처리  

## 📌 Tech

👉 https://github.com/kimhg990212/final_project

---

## 🛠 Tech Stack

### 💻 Backend
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">

### 🗄 Database
<img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">

### ⚙️ Tools
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">

---

## 📊 Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=seo02e&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=seo02e&layout=compact&theme=tokyonight)

---

## 📫 Contact

- ✉️ naver : seline21@naver.com  
- ✉️ gmail : kim0208154@gmail.com  

---

<div align="center">

🔥 꾸준히 성장하는 백엔드 개발자가 되겠습니다.

</div>

# 🐾 CodeTail

> Storytelling-based Personalized Coding Learning Platform

![CodeTail Banner](https://img.shields.io/badge/AI-Powered-blue)
![React](https://img.shields.io/badge/Frontend-React-61DAFB)
![Django](https://img.shields.io/badge/Backend-Django-092E20)
![Firebase](https://img.shields.io/badge/Database-Firebase-FFCA28)
![OpenAI](https://img.shields.io/badge/AI-ChatGPT-10A37F)

<br/>

## 📌 Overview

**CodeTail**은 스토리텔링 기반 AI 코딩 학습 플랫폼입니다.
사용자의 수준(Level Test), 학습 언어(Language Select), 그리고 선택한 스토리텔러(Teller)에 따라
개인화된 코딩 커리큘럼과 학습 경험을 제공합니다.

단순 문제 풀이 플랫폼이 아닌,

* 🎭 캐릭터 기반 스토리텔링
* 🤖 AI 기반 맞춤형 학습
* 📈 레벨 기반 커리큘럼
* 💡 코드 리뷰 및 리팩토링 피드백

을 결합하여 몰입감 있는 학습 경험을 목표로 합니다.

---
# 주요 UI
<img width="1288" height="777" alt="image" src="https://github.com/user-attachments/assets/2159e23b-812b-46cd-ab02-315a581ab209" />
<img width="1327" height="885" alt="image" src="https://github.com/user-attachments/assets/d5db5770-32f7-4167-93ac-cb3d90b1dd78" />
<img width="1365" height="896" alt="image" src="https://github.com/user-attachments/assets/a1aeb4a9-1a23-4f4e-b6cd-32e7be50f370" />

---
# ✨ Main Features

## 🎯 Personalized Curriculum

* AI 기반 사용자 수준 분석
* Level Test를 통한 실력 측정
* 개인별 맞춤 학습 경로 생성
* 학습 진행도(Progress Bar) 제공

---

## 🎭 Storytelling Learning

사용자는 원하는 스토리텔러(Teller)를 선택하여
각 캐릭터의 세계관에 맞는 코딩 학습을 진행할 수 있습니다.

예시:

* 🧙 Wizard Teller → 마법 세계 기반 알고리즘 학습
* 🚀 Space Teller → 우주 탐험 기반 자료구조 학습
* 🏴 Pirate Teller → 모험형 문제 해결 학습

---

## 💻 Interactive Coding Environment

* 웹 기반 코드 에디터 제공
* Run / Submit 기능
* Test Case 실행
* Compile 결과 확인
* 코드 저장 및 복구 기능
  
---

## 🤖 AI Code Review

사용자가 제출한 코드에 대해:

* 자동 채점
* 오류 분석
* 리팩토링 제안
* 효율성 피드백

을 AI 기반으로 제공합니다.

---

## 👨‍🏫 Teacher Mode

교육자는 AI를 활용하여:

* 학습 문제 생성
* 커리큘럼 구성
* 학습 자료 제작

을 진행할 수 있습니다.

---

# 🖼️ UI Preview

## Main Page

* 학생 / 교수 모드 선택
* 로그인 및 회원가입
* 서비스 소개

## Storytelling Page

* 스토리텔러 선택
* Progress 기반 학습 흐름
* Curriculum Visualization

## Coding Page

* 문제 확인
* 코드 작성
* 실행 / 제출 / 리뷰

## Teacher Page

* AI 문제 생성
* 조건 기반 문제 생성

> PPT의 실제 화면 캡처 이미지를 추가하면 README 완성도가 크게 향상됩니다.

---

# 🏗️ System Architecture

```text
┌────────────────────┐
│     React Frontend │
└─────────┬──────────┘
          │ REST API
┌─────────▼──────────┐
│    Django Backend  │
└─────────┬──────────┘
          │
 ┌────────▼────────┐
 │ Firebase / DB   │
 └────────┬────────┘
          │
 ┌────────▼────────┐
 │ ChatGPT API     │
 │ KoAlpaca Model  │
 └─────────────────┘
```

---

# ⚙️ Tech Stack

## Frontend

* React
* JavaScript
* HTML/CSS

## Backend

* Django
* REST API

## Database

* Firebase
* SQLite

## AI

* OpenAI ChatGPT API
* KoAlpaca-LoRA

## Collaboration

* GitHub
* Figma

---

# 📚 Functional Requirements

| ID  | Feature                     |
| --- | --------------------------- |
| F1  | Personalized Curriculum     |
| F2  | Learning Progress           |
| F3  | Storytelling-based Learning |
| F4  | Question Generation         |
| F5  | Code Edit & Run             |
| F6  | Code Submission             |
| F7  | AI Code Grading             |
| F8  | AI Code Review              |
| F9  | Level Test                  |
| F10 | Teller Select               |
| F11 | Language Select             |
| F12 | Login                       |
| F13 | Register                    |
| F14 | Mode Select                 |

---

# 🔄 User Flow

```text
Login
   ↓
Mode Select
   ↓
Language Select
   ↓
Level Test
   ↓
Teller Select
   ↓
Personalized Curriculum
   ↓
Storytelling Learning
   ↓
Code Practice
   ↓
AI Grading & Feedback
```

---

# 📂 Project Structure

```bash
CodeTail/
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── services/
│
├── backend/
│   ├── api/
│   ├── models/
│   ├── serializers/
│   └── services/
│
├── ai/
│   ├── prompt/
│   ├── grading/
│   └── storytelling/
│
├── docs/
│   ├── requirements/
│   ├── interface/
│   └── architecture/
│
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/SKKU-CodeTail/PROJECT_NAME.git
cd PROJECT_NAME
```

---

## 2. Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 3. Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

pip install -r requirements.txt

python manage.py runserver
```

---

# 📖 Documents

## Requirement Specification

* 요구사항 명세서 PDF 추가 예정

## Interface Specification

* 인터페이스 명세서 PDF 추가 예정

---

# 👥 Team

| Name | Role           |
| ---- | -------------- |
| 박성민  | Team Leader    |
| 김민석  | Frontend       |
| 서보현  | Backend        |
| 유현택  | AI Integration |
| 이재필  | Database       |
| 조성원  | Full Stack     |
| 채서영  | UI/UX          |

---

# 🌟 Expected Impact

CodeTail은 단순한 문제 풀이 플랫폼이 아닌,

* 재미(Fun)
* 몰입(Immersion)
* 개인화(Personalization)
* AI 기반 피드백(Intelligent Feedback)

을 결합하여 차세대 코딩 교육 플랫폼을 목표로 합니다.

---

# 📜 References

* React
* Django
* Firebase
* OpenAI ChatGPT
* KoAlpaca-LoRA

---

# 🐾 CodeTail

> Learn Coding Through Stories.

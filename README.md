# 🏆 LOCK-IN — 오늘의 갓생

> **하루 3가지 핵심 루틴 실천, AI 부메랑 사진 인증, 아바타 성장과 럭키박스, 한 달의 기록 모아보기까지!**  
> 모바일 환경에 최적화된 PWA 반응형 갓생 루틴 관리 웹 애플리케이션입니다.

---

## 🔗 서비스 링크 & 깃허브 저장소

- 🚀 **Vercel 배포 라이브 서비스**: [https://lock-in-gatsaeng.vercel.app](https://lock-in-gatsaeng.vercel.app)
- 💻 **GitHub Repository**: [https://github.com/Cheonghwa404/Link-In](https://github.com/Cheonghwa404/Link-In) (`main`, `main2` 브랜치)
- ⚡ **배포 플랫폼**: Vercel (Vercel Static & PWA)
- 🗄️ **데이터베이스 / 인증**: Supabase (PostgreSQL, Auth, RLS)

---

## ✨ 핵심 주요 기능

### 1. 📌 오늘의 3대 핵심 루틴 관리
- 하루 최대 **3개의 핵심 루틴**을 설정하고 집중 실천
- 루틴 생성/수정 시 **알람 피커**를 통한 맞춤 시간 설정 (오전/오후, 시/분, 퀵 +10분/+30분)
- 완료하지 못한 루틴을 다음 날로 손쉽게 넘기는 **루틴 토스(Pass) 기능**
- 매일, 평일, 주말, 지정 요일 반복 설정 지원

### 2. 📸 부메랑 사진 인증 & Gemini Vision AI 판독
- **1.5초 부메랑(Boomerang) 카메라** 촬영 기능
- 렌즈 상단에 오렌지 컬러의 **디지털 실시간 타임스탬프** 합성
- **Google Gemini Vision AI**를 이용한 미션 수행 자동 점수(Score) 및 위트 있는 피드백 반환
- API 키 미입력 시 가동되는 로컬 Mock 판정 모드 지원

### 3. 🎬 한 달의 기록 (인증 1.5초 움짤 모아보기)
- 루틴 완료 시 촬영된 **1.5초 부메랑 인증 움짤**을 모아 한 달간의 성수를 돌아보는 **비디오 하이라이트 플레이어**
- 릴스 형태의 캔버스 연속 재생, 미션 자망, 타임스탬프, 재생/일시정지/처음부터 다시보기 컨트롤
- 총 인증 개수, 하이라이트 총 분량(초), 갓생 실천 완수율 종합 통계 제공

### 4. 🌱 아바타 성장 & 스타일링 시스템
- 루틴 완수율에 따라 4단계로 귀엽게 성장하는 **새싹 아바타 SVG**
- **스킨 시스템**: 올 황금빛 골드🏆, 사이버 네온 블루💎, 슈렉 그린🟩, 에일리언 퍼플🟪
- **통나무 방 배경 교체**: 클래식 오크🏠, 딥 포레스트🌲, 빈티지 애쉬🪵
- **장신구 & 칭호**: 에어팟 맥스, 아령, 라떼, 땀밴드, 모던안경, 작심삼일 브레이커 등

### 5. 🎁 럭키박스(Gacha) & 아이템 확률표 모달
- 2코인으로 도전하는 **럭키박스 뽑기 시스템**
- 뽑기 버튼 좌측 **도움말 아이콘(`?`)** 클릭 시 등급별 확률표 모달 제공
- 미보유 아이템 우선 지급 및 중복 시 코인 환급 처리

### 6. 📱 PWA & 모바일 반응형
- Android Chrome 및 iOS Safari 완벽 대응
- iOS '홈 화면에 추가', Android '앱 설치' 지원
- 서비스워커(`sw.js`) 기반 오프라인 자산 캐시 처리

---

## 🎁 럭키박스 아이템 등급별 확률표

| 등급 | 확률 | 포함 아이템 목록 |
| :--- | :---: | :--- |
| 🌟 **전설 (Legendary)** | **10%** | 👑 오로라 왕관(한정), 🥽 레트로 선글라스(한정), 🏆 황금 골드, 💎 사이버 네온 블루, 🎧 네온 무지개 에어팟, 🌌 갤럭시 라떼, 🏋️‍♂️ 불타는 황금 아령, 🪵 빈티지 애쉬 |
| 💜 **영웅 (Epic)** | **25%** | 🟩 슈렉 그린, 🟪 에일리언 퍼플, 🍓 딸기 라떼, 🔮 득근 아령 (퍼플), 🍏 에어팟 맥스 (그린), 🌲 딥 포레스트 |
| 💙 **희귀 (Rare)** | **40%** | ☕ 아이스 아메리카노 (블랙), 🏋️‍♀️ 득근 아령 (블랙), 🎧 에어팟 맥스 (실버), 💦 땀 밴드, 👓 모던 안경, 🏠 클래식 오크 |
| ⚪ **일반 (Common)** | **25%** | 🪙 **1 코인 환급** (코인 소진 없이 재도전 가능) |

---

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend**: HTML5, CSS3 (Custom Design System & Glassmorphic UI), JavaScript (ES6+)
- **Icons**: Lucide Icons
- **Backend / Database**: Supabase (PostgreSQL, Row Level Security, Auth)
- **AI Vision Engine**: Google Gemini Vision API (`gemini-1.5-flash`)
- **PWA**: Service Worker, Web App Manifest
- **Deployment**: Vercel

---

## 🚀 Vercel 배포 방법 (How to Deploy on Vercel)

### 방법 1. Vercel 대시보드 웹 배포 (추천)
1. [Vercel Dashboard](https://vercel.com/new) 접속 및 로그인
2. GitHub 저장소 연동 (`Cheonghwa404/Link-In`) 선택
3. **Branch**: `main` 또는 `main2` 선택
4. Framework Preset: **Other** (Static HTML/JS/CSS)
5. Root Directory: `./complete` (또는 `./`) 설정 후 **Deploy** 클릭!

### 방법 2. Vercel CLI 배포
```bash
# Vercel CLI 설치 및 로그인
npm install -g vercel
vercel login

# 배포 실행 (Production)
vercel --prod
```

---

## 📂 프로젝트 구조 (Project Directory)

```text
complete/
├── index.html          # 메인 UI 레이아웃 및 모달 구조
├── style.css           # 갓생 모바일 디자인 시스템 & 커스텀 애니메이션
├── app.js              # 루틴 관리, 카메라 인증, 비디오 플레이어, 이달의 잔디
├── store.js            # GodsaengStore (로컬스토리지 & Supabase 뷰 동기화)
├── avatar.js           # 동적 SVG 아바타 & 착용 아이템 렌더러
├── ai.js               # Gemini Vision AI 판독 연동
├── manifest.json       # PWA 설치 매니페스트
├── sw.js               # Service Worker 오프라인 자산 캐시
└── vercel.json         # Vercel 배포 헤더 및 라우팅 설정
```

---

## 📝 라이선스 (License)

Copyright © 2026 LOCK-IN Team. All rights reserved.

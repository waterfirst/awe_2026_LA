# AWE 2026 Long Beach — AI 출장 보고서 템플릿

> **AWE USA 2026** · Long Beach Convention Center, CA · **2026.06.15–18**  
> 테마: *"Humans Empowered by Spatial AI"* · 5,000+ 참가자 · 250+ 전시업체  
> 공식사이트: https://www.awexr.com/usa-2026

---

## 🎯 이 템플릿이란?

현장에서 모은 **사진 + 메모**를 [Antigravity](https://antigravity.google/)에 넣으면  
`index.html` 보고서가 자동 완성되고 GitHub Pages로 배포까지 한 번에 됩니다.

---

## 📂 폴더 구조

```
awe_2026_LA/
├── index.html          ← 보고서 본문 (탭 4개)
├── notes/
│   ├── schedule.txt    ← 일정 메모
│   ├── exhibition.txt  ← 전시 센싱 메모  ← 현장에서 여기 기록!
│   └── vip_meeting.txt ← VIP 미팅 메모   ← 현장에서 여기 기록!
├── img/
│   ├── day1/           ← 1일차 사진
│   ├── day2/           ← 2일차 사진
│   ├── exhibition/     ← 부스 사진
│   └── vip/            ← 미팅 사진
└── papers/             ← 수집한 자료·카탈로그 PDF
```

---

## 🚀 사용 방법 (Zoom 세션 가이드)

### 1단계 (5분) — GitHub 계정 만들기
1. https://github.com 접속 → **Sign up**
2. 이메일 / 비밀번호 / 사용자명 입력 후 가입

### 2단계 (5분) — 이 템플릿 Fork
1. https://github.com/waterfirst/awe_2026_LA 접속
2. 오른쪽 위 **Fork** 버튼 클릭
3. **Repository name** → 본인 이름으로 변경 (예: `awe_2026_LA_김영재`)
4. **Create fork** 클릭

### 3단계 (10분) — 폴더 구조 이해
현장에서 이렇게 저장하세요:

| 저장할 것 | 저장 위치 |
|---|---|
| 부스 사진 | `img/exhibition/` |
| VIP 미팅 사진 | `img/vip/` |
| 일별 사진 | `img/day1/`, `img/day2/` … |
| 전시 센싱 메모 | `notes/exhibition.txt` |
| VIP 미팅 메모 | `notes/vip_meeting.txt` |
| 수집 자료·팸플릿 | `papers/` |

> 💡 **현장 팁**: 사진 찍을 때 파일명을 `부스명_번호.jpg` 형식으로 저장하면 Antigravity가 자동으로 매핑합니다.

### 4단계 (30분) — Antigravity로 보고서 작성

#### 4-1. Antigravity 설치
1. https://antigravity.google/ 접속
2. 본인 PC에 다운로드 · 설치
3. 구글 계정으로 로그인

#### 4-2. 프로젝트 열기
1. Antigravity 실행
2. **Open Folder** → Fork한 `awe_2026_LA_본인이름` 폴더 선택
3. 왼쪽 파일 탐색기에 전체 폴더가 보이면 준비 완료

#### 4-3. 아래 프롬프트를 Antigravity 채팅창에 복붙

```
너는 AWE 2026 Long Beach 출장 보고서 작성 전문가야.

다음 파일들을 읽어서 index.html의 보고서 내용을 완성해줘:
- notes/exhibition.txt (전시 센싱 메모)
- notes/vip_meeting.txt (VIP 미팅 메모)  
- notes/schedule.txt (일정)
- img/ 폴더의 모든 사진

작업 내용:
1. index.html에서 [대괄호로 감싼 모든 플레이스홀더]를 실제 내용으로 교체
2. 전시 센싱 섹션: 부스별 카드를 notes/exhibition.txt 내용으로 채워줘
3. VIP 미팅 섹션: notes/vip_meeting.txt 내용으로 미팅 카드를 완성해줘
4. 일정 섹션: notes/schedule.txt 내용으로 Day별 이벤트를 채워줘
5. 사진은 img/ 폴더에 맞는 위치에 <img src="img/..."> 태그로 삽입해줘
6. 최종 소감 섹션: 전체 출장 내용을 종합해 핵심 인사이트 3가지와 Action Items를 작성해줘
7. 최종 결과물은 index.html 하나의 파일로 저장해줘

HTML 파일 스타일(색상, 탭 구조, CSS)은 절대 변경하지 마. 내용만 채워줘.
```

#### 4-4. 생성 확인
- Antigravity가 `index.html`을 수정
- 채팅창에서 "완료" 메시지 확인
- 브라우저로 `index.html` 열어서 내용 확인

### 5단계 (10분) — GitHub에 업로드

#### 방법 A: GitHub 웹에서 직접 업로드
1. 본인 Fork 저장소 접속
2. `index.html` 파일 클릭 → 연필(✏️) 아이콘
3. 내용 전체 선택 후 Antigravity가 수정한 내용으로 붙여넣기
4. **Commit changes** 클릭

#### 방법 B: 폴더 통째로 드래그
1. 저장소 메인 페이지에서 **Add file → Upload files**
2. `img/` 폴더 전체를 드래그 앤 드롭
3. **Commit changes** 클릭

### 6단계 (5분) — GitHub Pages로 배포
1. 저장소 → **Settings** 탭
2. 왼쪽 메뉴 **Pages** 클릭
3. **Source** → `Deploy from a branch`
4. **Branch** → `main` / `/ (root)` 선택
5. **Save** 클릭
6. 1~2분 후 `https://[본인아이디].github.io/awe_2026_LA_본인이름/` URL 생성!

---

## 📋 Antigravity 추가 프롬프트 (선택)

**사진 캡션 자동 생성:**
```
img/exhibition/ 폴더의 사진들을 분석해서 각 사진에 적합한 한국어 캡션을 달아줘.
형식: 부스명 - 제품명/기술명 설명
```

**경쟁사 비교표 자동 완성:**
```
notes/exhibition.txt의 부스 정보를 바탕으로 경쟁사 비교표를 만들어줘.
컬럼: 회사명, 핵심 기술, 강점, 약점, 우리 회사에 대한 시사점
HTML <table> 형식으로 index.html의 전시센싱 탭 안에 삽입해줘.
```

**Action Items 이메일 초안:**
```
VIP 미팅 내용(notes/vip_meeting.txt)을 바탕으로 
각 미팅 상대방에게 보낼 Follow-up 이메일 초안을 한국어로 작성해줘.
```

---

## ⚡ 현장에서 바로 쓰는 메모 양식

**전시 센싱** (notes/exhibition.txt에 추가):
```
[부스명]: Meta Quest Pro 3
[위치]: 홀 A, A-123
[핵심 기술]: 눈 추적 + 손 제스처 인식 개선
[고객/관람객 반응]: 체험 줄이 30분 이상, 매우 관심 높음
[경쟁사 동향]: Apple Vision Pro보다 가격 50% 저렴
[특이사항]: 한국 파트너 문의 부스에 있음
[사진 파일명]: meta_quest_01.jpg, meta_quest_02.jpg
```

**VIP 미팅** (notes/vip_meeting.txt에 추가):
```
[일시]: 2026-06-16 14:00
[상대방/회사]: John Smith / XR Displays Inc.
[미팅 목적]: 패널 공급 논의
[주요 논의 내용]: 마이크로 LED 샘플 요청, Q3 납기 협의
[Action Items]: 샘플 사양서 6/20까지 발송, NDA 계약 검토
[Follow-up]: 6월 말 화상 미팅 확정
```

---

## 🛠 문제 해결

| 문제 | 해결 방법 |
|---|---|
| Antigravity 무료 토큰 한도 초과 | 유료 플랜($20/월) 또는 구글 AI Studio API 키 연결 |
| 사진이 보이지 않음 | 파일명 한글/공백 제거 → 영문+숫자+언더스코어만 사용 |
| GitHub Pages URL 안 열림 | 1~3분 대기 후 새로고침 |
| index.html 내용이 안 바뀜 | Antigravity에서 파일 저장(Ctrl+S) 확인 |

---

## 👤 만든 사람

최낙초 (nakcho.choi@gmail.com) — AI 세미나 2026.06.13  
참고: [SID Display Week 2026 보고서](https://github.com/waterfirst/sid-display-week-2026)

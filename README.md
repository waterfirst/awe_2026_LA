# AWE USA 2026 — AI 출장보고서 템플릿

> **AWE USA 2026** · Long Beach Convention Center, CA  
> **June 15–18, 2026** · 테마: *"I, Spatial — Humans Empowered by Spatial AI"*  
> 5,000+ 참가자 · 250+ 전시업체 · 400+ 연사  
> 공식 사이트: https://www.awexr.com/usa-2026

---

## 이 템플릿이 하는 일

현장에서 모은 **사진 + 메모**를 AI(Antigravity)에 넣으면  
→ `index.html` 출장보고서가 **자동 완성**되고  
→ GitHub Pages로 **웹 URL이 생성**됩니다.

**완성 예시 (SID 2026):** [https://waterfirst.github.io/awe_2026_LA/](https://waterfirst.github.io/awe_2026_LA/)

---

## 📋 전체 흐름 (6단계)

```
1단계  GitHub 계정 만들기          (5분, PC에서 1회만)
2단계  이 레포 Fork                (2분)
3단계  현장 자료 수집              (출장 내내)
4단계  Antigravity 가입            (5분, 1회만)
5단계  AI로 보고서 생성            (30~60분)
6단계  GitHub Pages 배포           (5분)
```

---

## 1단계 — GitHub 계정 만들기

> ✅ 이미 GitHub 계정이 있으면 2단계로 건너뜀

1. **https://github.com** 접속
2. 우측 상단 **Sign up** 클릭
3. 이메일 주소 입력 → 비밀번호 설정 → 사용자 이름(영문) 입력
4. 이메일 인증 완료
5. 무료 플랜(Free) 선택

> 💡 사용자 이름이 URL에 포함됩니다: `[내 아이디].github.io/awe_2026_LA`

---

## 2단계 — 템플릿 가져오기

두 가지 방법 중 하나를 선택합니다.

| | 방법 A — Fork + ZIP | 방법 B — Clone |
|---|---|---|
| 난이도 | 쉬움 (클릭만) | 보통 (Git 명령어) |
| GitHub 계정 필요 | 필요 | 필요 |
| Git 설치 필요 | **불필요** | 필요 |
| 로컬 작업 방법 | ZIP 압축 해제 후 폴더 편집 | git clone |
| GitHub 업로드 방법 | 웹에서 드래그 앤 드롭 | git push |
| 추천 대상 | **비개발자 (대부분)** | Git 익숙한 분 |

---

### 방법 A — Fork + ZIP 다운로드 (비개발자 추천)

**전체 흐름: Fork(GitHub 복사) → ZIP 다운로드 → 로컬 폴더 작업 → 웹 업로드**

#### A-1. Fork — GitHub에서 내 계정으로 복사

1. 이 페이지 상단 우측 **Fork** 버튼 클릭

   ```
   [Watch]  [Star]  [Fork ▼]
   ```

2. **Owner** 에서 본인 계정 선택 → **Create fork** 클릭

3. 잠시 후 `https://github.com/[내 아이디]/awe_2026_LA` 로 이동됨

> ✅ GitHub에 내 소유 복사본이 생겼습니다. Git 없이도 이용 가능합니다.

#### A-2. ZIP 다운로드 — 로컬 PC로 가져오기

1. 내 Fork 레포(`github.com/[내 아이디]/awe_2026_LA`) 접속
2. 초록색 **Code ▼** 버튼 클릭
3. **Download ZIP** 클릭

   ```
   Code ▼
   ├── Open with GitHub Desktop
   ├── Open with Codespace
   └── ⬇ Download ZIP   ← 이것 클릭
   ```

4. 다운로드된 `awe_2026_LA-main.zip` 압축 해제
5. 폴더 이름 `awe_2026_LA-main` → `awe_2026_LA` 로 변경 (선택)

> ✅ 이제 내 PC에 `awe_2026_LA/` 폴더가 생겼습니다.

#### A-3. 로컬 폴더에 사진·메모 넣기

압축 해제한 폴더에 파일을 직접 넣습니다:

```
awe_2026_LA/
├── img/
│   ├── day1/   ← 이동일 사진 여기에 복붙
│   ├── day2/   ← 전시 첫날 사진
│   └── ...
└── notes/
    ├── exhibition.txt   ← 메모장으로 열어서 내용 채우기
    └── vip_meeting.txt
```

#### A-4. Antigravity로 보고서 생성

`awe_2026_LA/` 폴더 전체를 Antigravity에 업로드 → 프롬프트 입력 → `index.html` 다운로드  
(자세한 방법은 5단계 참조)

#### A-5. GitHub에 파일 올리기 (Git 불필요)

**방법 ①: index.html만 교체 (가장 빠름)**

1. 내 Fork 레포 접속 → `index.html` 파일 이름 클릭
2. 우측 ✏️ 연필 아이콘 클릭
3. 전체 선택(Ctrl+A) → Antigravity에서 받은 내용 붙여넣기
4. **Commit changes** 클릭 → 완료 ✅

**방법 ②: 파일 여러 개 한 번에 올리기**

1. 내 Fork 레포 접속
2. **Add file ▼ → Upload files** 클릭
3. `index.html` + 사진 파일들 드래그 앤 드롭
4. **Commit changes** 클릭 → 완료 ✅

> ✅ 커밋하면 GitHub Pages URL이 1~2분 안에 자동 업데이트됩니다.

---

### 방법 B — Clone (Git 사용자용)

**Clone = 로컬 PC로 직접 다운로드 후 내 레포에 올리기**

#### B-1. Git 설치 확인

```bash
git --version
# git version 2.x.x 가 나오면 설치됨
```

설치 안 됐다면: https://git-scm.com/downloads 에서 다운로드

#### B-2. 클론

```bash
# 원하는 폴더로 이동 후
git clone https://github.com/waterfirst/awe_2026_LA.git
cd awe_2026_LA
```

#### B-3. 내 GitHub에 새 레포 만들기

1. https://github.com/new 접속
2. Repository name: `awe_2026_LA` 입력
3. **Public** 선택 (GitHub Pages 무료 배포에 필요)
4. **README 체크 해제** (이미 있으므로)
5. **Create repository** 클릭

#### B-4. 원격 주소를 내 레포로 변경

```bash
# 기존 원본 연결 제거 후 내 레포로 교체
git remote remove origin
git remote add origin https://github.com/[내 아이디]/awe_2026_LA.git

# 내 레포로 업로드
git push -u origin main
```

> 💡 `[내 아이디]` 자리에 본인 GitHub 사용자 이름 입력  
> 예) `git remote add origin https://github.com/hong-gildong/awe_2026_LA.git`

#### B-5. 이후 작업 (사진·메모 추가할 때마다)

```bash
# 파일 추가/수정 후
git add .
git commit -m "사진 및 메모 추가"
git push origin main
```

> ✅ Push 할 때마다 GitHub Pages가 자동으로 업데이트됩니다.

---

#### 나중에 원본 업데이트 반영하기 (선택사항)

```bash
# 원본 레포를 upstream으로 등록 (최초 1회)
git remote add upstream https://github.com/waterfirst/awe_2026_LA.git

# 원본의 최신 변경사항 가져오기
git fetch upstream
git merge upstream/main
git push origin main
```

---

## 3단계 — 현장 자료 수집 (출장 중)

### 📁 폴더 구조

```
awe_2026_LA/
├── index.html              ← 보고서 본문 (탭 4개: 일정/센싱/주목기업/소감)
├── zoom_guide.html         ← Zoom 교육 슬라이드 (이 안내서 발표용)
│
├── img/                    ← 사진 폴더
│   ├── day1/               ← Jun 14 이동일 사진
│   ├── day2/               ← Jun 15 Workshops/Welcome Party 사진
│   ├── day3/               ← Jun 16 키노트/Expo Hall 사진
│   ├── day4/               ← Jun 17 Expo Hall 사진
│   ├── exhibition/         ← 전시 부스 사진 (날짜 무관)
│   └── vip/                ← VIP 미팅 사진
│
├── notes/                  ← 메모 파일
│   ├── schedule.txt        ← 일정 메모
│   ├── exhibition.txt      ← 전시 부스 센싱 메모  ← ⭐ 가장 중요
│   ├── vip_meeting.txt     ← VIP 미팅 메모
│   └── meetings.txt        ← 일반 미팅 메모
│
└── papers/                 ← 수집 자료, 팸플릿 PDF 등
```

### 📸 사진 찍는 요령

| 상황 | 파일명 예시 |
|------|------------|
| 부스 전경 | `img/exhibition/META_booth_overview.jpg` |
| 제품 클로즈업 | `img/exhibition/META_orion_front.jpg` |
| 시연 장면 | `img/exhibition/snap_spectacles_demo.jpg` |
| 키노트 | `img/day3/keynote_evan_spiegel.jpg` |
| VIP 미팅 | `img/vip/snap_meeting.jpg` |

> 💡 **파일명에 공백 금지** — 언더스코어(`_`) 사용  
> 💡 **JPG 권장** — PNG는 용량이 커서 느려질 수 있음  
> 💡 **iPhone HEIC 파일** → 카메라 설정에서 JPEG로 변경하거나 변환 후 업로드

### 📝 notes/ 메모 작성법

**exhibition.txt** — 부스마다 하나씩 작성:

```
[부스명: META Reality Labs]  ★★★
위치: Hall A, 부스 101
제품/기술: Orion AR 글래스
핵심 스펙: FOV 70°, 무게 98g, 공간오디오 내장
고객 반응: 대기줄 30분, 체험 후 "생각보다 가볍다" 반응 多
인상/분석: 웨이브가이드 대비 홀로그래픽 소자 방식이 선명도 압도
사진: META_booth_overview.jpg, META_orion_front.jpg
---
```

**vip_meeting.txt** — 미팅마다 하나씩:

```
[기업명: Snap Inc.]
미팅 일시: Jun 16, 14:00
장소: Snap 부스 미팅룸
상대방 직함: 파트너십 디렉터
미팅 목적: Spectacles 차기작 디스플레이 공급 가능성 타진
주요 내용:
- 내년 Spectacles Gen4 계획 중, 디스플레이 밝기 최대 관심사
- 현재 마이크로LED 공급사 모색 중
자사 연관성: 당사 마이크로OLED가 FOV·밝기 요건 충족 가능
후속 조치: NDA 후 스펙 공유 요청 (담당: 홍길동, 7/31까지)
---
```

---

## 4단계 — Antigravity 가입

**Antigravity = Google이 만든 AI 코딩 도구 (코딩 불필요)**

1. **https://antigravity.google** 접속
2. **Sign in with Google** 클릭
3. Gmail 계정으로 로그인 (회사 이메일 또는 개인 Gmail 모두 가능)
4. 완료 ✅

> ⚠️ 무료 플랜도 출장 보고서 1개 생성에는 충분합니다  
> 사진 파일 총합이 500MB 초과 시 유료 플랜($20/월) 필요

---

## 5단계 — Antigravity로 보고서 생성

### 5-1. 폴더 준비

내 Fork 레포에서 ZIP을 받아 사진·메모를 넣습니다:

1. 내 Fork 레포 (`github.com/[내 아이디]/awe_2026_LA`) 접속
2. 초록 **Code ▼ → Download ZIP** 클릭 → 압축 해제
3. 아래처럼 파일 넣기:

```
awe_2026_LA/
  ├── notes/
  │   ├── exhibition.txt    ← 메모장으로 열어서 내용 채우기
  │   └── vip_meeting.txt   ← 미팅 메모 채우기
  └── img/
      ├── day3/
      │   └── keynote_evan_spiegel.jpg   ← 사진 복붙
      ├── exhibition/
      │   ├── META_booth.jpg
      │   └── snap_spectacles.jpg
      └── vip/
          └── snap_meeting.jpg
```

### 5-2. Antigravity 업로드

1. https://antigravity.google 접속 → **New Project** 클릭
2. `awe_2026_LA` 폴더 전체를 **드래그 앤 드롭**
3. 업로드 완료 대기 (30초~3분)

### 5-3. 프롬프트 선택 (복붙용)

**📌 나중에 GitHub에 올릴 계획이면 → 프롬프트 A**  
**📌 Antigravity에서 바로 공유할 계획이면 → 프롬프트 A 또는 B 모두 가능**

---

**프롬프트 A — 기본 (사진을 img/ 폴더로 관리)**

```
notes/ 폴더 메모와 img/ 폴더 사진을 바탕으로 index.html 출장보고서를 완성해줘.

규칙:
1. 탭 구성 유지 (일정 / 전시센싱 / 주목기업 / 최종소감)
2. 모든 [ ] 플레이스홀더를 실제 내용으로 교체
3. img/ 사진을 날짜별로 해당 섹션에 배치
4. exhibition.txt 내용을 전시센싱 탭에 반영
5. vip_meeting.txt 내용을 주목기업 탭에 반영
6. 단일 HTML 파일로 출력
7. 다크 테마 · 탭 구조 · 스플래시 스크린 유지
```

---

**프롬프트 B — 사진 내장형 ⭐ (초보자 강력 추천)**

> 사진을 HTML 파일 안에 통째로 넣어버려서 **파일 하나만 올리면 끝**입니다.  
> 사진을 따로 업로드할 필요가 없습니다.

```
notes/ 폴더 메모와 img/ 폴더 사진을 바탕으로 index.html 출장보고서를 완성해줘.

규칙:
1. 탭 구성 유지 (일정 / 전시센싱 / 주목기업 / 최종소감)
2. 모든 [ ] 플레이스홀더를 실제 내용으로 교체
3. 모든 사진을 Base64로 인코딩해서 HTML 파일 안에 직접 내장
   (외부 img/ 폴더 참조 없이 index.html 하나로 동작하게)
4. exhibition.txt 내용을 전시센싱 탭에 반영
5. vip_meeting.txt 내용을 주목기업 탭에 반영
6. 단일 HTML 파일로 출력
7. 다크 테마 · 탭 구조 · 스플래시 스크린 유지
```

> ⚠️ 사진이 많으면 index.html 파일 크기가 커질 수 있습니다 (사진 10장 기준 약 5~15MB)

---

### 5-4. index.html 다운로드

Antigravity가 생성한 `index.html` 파일을 PC에 저장합니다.

---

## 6단계 — 보고서 공유하기

> 3가지 방법 중 본인 상황에 맞는 것을 선택하세요.

---

### 🥇 방법 1 — Antigravity에서 바로 공유 (가장 쉬움)

**Git 불필요 · GitHub 불필요 · 클릭 한 번**

Antigravity 작업이 끝난 화면에서:

```
우측 상단 또는 하단의 "Publish" / "Share" / "Deploy" 버튼 클릭
→ URL 즉시 발급
   예) https://[프로젝트명].antigravity.google
→ 이 URL을 카카오톡·이메일로 공유 ✅
```

> ✅ 추가 설치 없이 지금 당장 공유 가능  
> ℹ️ URL 형식이 github.io가 아닌 antigravity.google 도메인

---

### 🥈 방법 2 — GitHub에 올리기 (브라우저만, Git 불필요)

**GitHub Pages URL: `[내 아이디].github.io/awe_2026_LA`**

#### 2-1. index.html 업로드

**사진 내장형(프롬프트 B)으로 만들었다면 → index.html 1개만 올리면 끝!**

1. 내 Fork 레포(`github.com/[내 아이디]/awe_2026_LA`) 접속
2. **Add file ▼ → Upload files** 클릭

   ```
   [내 레포 메인 화면]
   Code  Issues  Pull requests  ...  ← 상단 탭들
   
   [Go to file]  [Add file ▼]  [<> Code ▼]   ← 여기서 Add file 클릭
                  ├── Create new file
                  └── Upload files   ← 이것 클릭
   ```

3. Antigravity에서 받은 `index.html` 파일을 화면 안으로 **드래그 앤 드롭**
4. 하단 **Commit changes** 클릭 (기본값 그대로 → 초록 버튼)
5. 1~2분 기다리면 GitHub Pages URL 자동 업데이트 ✅

**사진을 따로 올려야 하는 경우(프롬프트 A 사용 시):**

```
레포 → img/ 폴더 클릭 → day1/ 폴더 클릭
→ Add file → Upload files → 사진 드래그
→ Commit changes
(날짜 폴더마다 반복)
```

#### 2-2. GitHub Pages 활성화 (최초 1회만)

> ✅ 이미 Fork할 때 설정했으면 이 단계 건너뜀

1. 레포 상단 **⚙️ Settings** 탭 클릭
2. 왼쪽 메뉴 아래쪽 → **Pages** 클릭
3. **Source**: `Deploy from a branch` 선택
4. **Branch**: `main` / **폴더**: `/ (root)` → **Save**
5. 1~3분 후 아래 문구와 함께 URL 생성:

```
🎉  Your site is live at:
    https://[내 아이디].github.io/awe_2026_LA
```

---

### 🥉 방법 3 — git push (개발자용)

**Git이 설치된 분만 사용**

```bash
# 파일 수정 후 레포 폴더에서:
git add .
git commit -m "보고서 완성"
git push origin main
# → GitHub Pages 자동 업데이트
```

---

### 방법 비교 한눈에 보기

| | 방법 1 (Antigravity Publish) | 방법 2 (GitHub 웹 업로드) | 방법 3 (git push) |
|---|---|---|---|
| Git 설치 | 불필요 | 불필요 | **필요** |
| 난이도 | ⭐ 매우 쉬움 | ⭐⭐ 쉬움 | ⭐⭐⭐ 보통 |
| URL 형식 | antigravity.google/... | github.io/... | github.io/... |
| 사진 별도 업로드 | 불필요 | 내장형이면 불필요 | 내장형이면 불필요 |
| 추천 대상 | 모든 분 | 비개발자 | 개발자 |

---

## 🔗 팀 공유

완성된 URL을 Slack·카카오톡·이메일로 공유:

```
AWE 2026 출장 보고서 — [이름]
https://[내 아이디].github.io/awe_2026_LA
```

> 스마트폰·태블릿에서도 반응형으로 잘 보입니다

---

## ❓ 자주 묻는 질문

**Q. GitHub Pages URL이 안 보여요**  
A. Settings → Pages 에서 Branch를 `main`으로 설정했는지 확인. 설정 후 최대 5분 소요.

**Q. Antigravity에서 "파일이 너무 크다"고 해요**  
A. 사진 해상도를 낮추거나 (300~500KB 이하 권장), 사진 수를 줄여보세요.  
iPhone 사진은 HEIC → JPG로 변환 후 업로드 권장.

**Q. 사진이 보고서에 안 나와요**  
A. 파일명에 한글·공백이 없는지 확인.  
예) `META 부스.jpg` (❌) → `META_booth.jpg` (✅)

**Q. 보고서를 다른 사람도 수정하게 하려면?**  
A. 레포 Settings → Collaborators → 상대방 GitHub 아이디 또는 이메일로 초대

**Q. 내 보고서 내용이 원본 waterfirst 레포에 올라가나요?**  
A. 아닙니다. Fork는 완전히 독립된 내 레포입니다. 원본에는 전혀 영향 없습니다.

**Q. 보고서를 비공개로 만들 수 있나요?**  
A. GitHub 무료 계정에서는 Private 레포에 GitHub Pages 불가.  
비공개로 하려면 GitHub Pro($4/월) 또는 URL 자체를 공유 안 하면 됩니다.

---

## 👥 팀 통합 보고서 만들기 (10~13명 → 1명 취합)

> 한 명이 팀 전체 자료를 모아 **하나의 완성된 팀 보고서**를 만드는 방법

### 전체 흐름

```
각자 출장 중        →   출장 후           →    취합 담당자          →   완성
─────────────           ─────────────         ─────────────────         ─────────
사진 찍기               사진 이름 변경         팀 폴더 구성               Antigravity로
메모 작성   →  →  →    메모 작성 완성   →  →  모든 파일 수령      →  →  팀 보고서 생성
                        압축 후 전송            members/ 에 정리           GitHub 배포
```

---

### A. 각자 할 일 (참가자 전원 — 출장 중~후)

#### A-1. 사진 파일명 규칙 (★ 가장 중요)

반드시 **이름_부스명_설명.jpg** 형식으로 저장합니다.

```
❌ 하지 말 것          ✅ 이렇게 하세요
────────────────       ────────────────────────────────
IMG_4821.jpg      →   홍길동_META_booth_overview.jpg
사진.jpg           →   김철수_snap_spectacles_demo.jpg
KakaoTalk_Photo.jpg → 이영희_sony_spatial_audio_front.jpg
스크린샷.png       →   박민수_keynote_evan_spiegel.jpg
```

**규칙 요약:**
- 이름 + 언더스코어(`_`) + 부스명 + 언더스코어 + 설명
- 한글 이름 사용 가능 (단, 공백은 언더스코어로)
- 확장자는 `.jpg` 또는 `.jpeg` 권장 (PNG도 가능)
- iPhone HEIC 파일은 반드시 JPG로 변환 후 전송

**iPhone HEIC → JPG 변환 방법 (iOS 설정 앱에서):**
```
설정 → 카메라 → 포맷 → "호환성 우선" 선택
(이렇게 하면 이후로 자동 JPG로 저장)

이미 찍은 HEIC 파일 변환:
아이폰 → 사진 앱 → AirDrop으로 Mac 전송 시 자동 JPG 변환
또는: 구글 드라이브에 올리면 JPG로 변환됨
```

#### A-2. 메모 작성 (notes/ 양식 사용)

**exhibition.txt** — 본인이 센싱한 부스마다 하나의 블록:

```
[부스명: 회사이름]  ★★★ (★ 1~5개로 중요도 표시)
작성자: 홍길동
위치: Hall A / B / C, 부스번호 (모르면 생략)
제품/기술: 한 줄 요약
핵심 스펙/특징:
- 포인트 1
- 포인트 2
시연 내용: 직접 체험했다면 경험 서술
인상/분석: 당사 사업과의 연관성, 경쟁사 동향 등
사진파일: 홍길동_META_booth_overview.jpg, 홍길동_META_orion_front.jpg
---
```

**vip_meeting.txt** — 본인이 참석한 미팅:

```
[기업명]
작성자: 홍길동
미팅 일시: Jun 16, 14:00
상대방: 직함 (실명 기재 여부는 담당자 판단)
미팅 목적: 한 줄
주요 내용:
- 내용 1
- 내용 2
후속 조치: 담당자명, 기한
사진파일: 홍길동_snap_meeting.jpg
---
```

#### A-3. 파일 전송 방법 (참가자 → 취합 담당자)

**방법 1: 카카오톡 (가장 쉬움)**
```
카카오톡 단톡방에 파일 전송 시 주의사항:
- 사진은 반드시 "파일로 전송" (앨범으로 올리면 파일명이 바뀜!)
  카카오톡 → + 버튼 → 파일 → 사진 선택
- 텍스트 파일(exhibition.txt)도 파일로 전송
- 한 번에 최대 20개 → 여러 번 나눠서 전송 가능
```

**방법 2: 구글 드라이브 공유 폴더 (추천 — 파일명 보존)**
```
1. 취합 담당자가 Google Drive에 "AWE2026_팀자료" 폴더 생성
2. 팀원에게 편집 링크 공유
3. 각자 본인 이름 폴더 만들고 업로드:
   AWE2026_팀자료/
   ├── 홍길동/
   │   ├── 홍길동_META_booth.jpg
   │   └── exhibition.txt
   └── 김철수/
       ├── 김철수_snap_demo.jpg
       └── exhibition.txt
```

**방법 3: WeTransfer (대용량)**
```
https://wetransfer.com (무료, 최대 2GB)
1. 파일 첨부 → 수신자 이메일 입력 → 전송
2. 다운로드 링크 7일간 유효
```

---

### B. 취합 담당자가 할 일

#### B-1. 폴더 구성

다운로드한 `awe_2026_LA` 폴더 안에 아래처럼 정리합니다:

```
awe_2026_LA/
├── index.html              ← 보고서 본문 (건드리지 않음)
│
├── members/                ← ★ 새로 만드는 팀원 폴더
│   ├── 홍길동/
│   │   ├── exhibition.txt
│   │   ├── vip_meeting.txt (있으면)
│   │   ├── 홍길동_META_booth_overview.jpg
│   │   ├── 홍길동_META_orion_front.jpg
│   │   └── 홍길동_snap_spectacles_demo.jpg
│   │
│   ├── 김철수/
│   │   ├── exhibition.txt
│   │   ├── 김철수_sony_booth.jpg
│   │   └── 김철수_keynote_spiegel.jpg
│   │
│   ├── 이영희/
│   │   ├── exhibition.txt
│   │   ├── vip_meeting.txt
│   │   └── 이영희_qualcomm_xr2.jpg
│   │
│   └── ... (나머지 팀원들)
│
├── team_notes/             ← 취합 담당자가 만드는 폴더
│   ├── team_exhibition.txt ← 모든 exhibition.txt 내용을 하나로 합친 파일
│   └── team_vip.txt        ← 모든 vip_meeting.txt 내용을 하나로 합친 파일
│
└── img/                    ← 기존 구조 유지
    └── ...
```

#### B-2. team_exhibition.txt 만들기

각 팀원의 `exhibition.txt`를 **메모장/TextEdit에서 열어** 내용을 하나씩 복사 붙여넣기:

```
===== 팀 AWE 2026 전시 센싱 통합 메모 =====
작성일: 2026-06-20
참가자: 홍길동, 김철수, 이영희, 박민수, ... (전원 이름 나열)
총 센싱 부스 수: 약 XX개

── 홍길동 센싱 ──────────────────────────
[부스명: META Reality Labs]  ★★★★
작성자: 홍길동
...내용...
---

[부스명: Snap Inc.]  ★★★★★
작성자: 홍길동
...내용...
---

── 김철수 센싱 ──────────────────────────
[부스명: Sony XR Division]  ★★★
작성자: 김철수
...내용...
---

── 이영희 센싱 ──────────────────────────
...
```

> 💡 같은 부스를 여러 명이 방문한 경우: **그냥 두세요.** AI가 알아서 종합합니다.

#### B-3. Antigravity에 업로드

1. https://antigravity.google 접속
2. **New Project** 클릭
3. `awe_2026_LA` 폴더 전체 드래그 앤 드롭
   - `members/` 폴더 포함 전체 업로드
   - 사진 수가 많으면 몇 분 걸릴 수 있음 (팀 인원 × 사진 수)
4. 업로드 완료 후 아래 프롬프트 입력

---

### C. Antigravity 프롬프트 (복붙용)

#### 프롬프트 1 — 팀 통합 보고서 초안 생성

```
아래 지시에 따라 index.html 팀 출장 보고서를 완성해줘.

[데이터 소스]
- members/ 폴더: 팀원 10명 이상의 개인 사진과 메모
- team_notes/team_exhibition.txt: 전체 전시 센싱 통합 메모
- team_notes/team_vip.txt: 전체 VIP 미팅 통합 메모

[작업 지시]
1. 전시센싱 탭: team_exhibition.txt 내용을 회사/제품별로 정리
   - 같은 부스를 여러 명이 작성했으면 내용을 합쳐서 종합 평가 작성
   - ★★★★★ ~ ★ 순으로 중요도 정렬
   - 각 부스 대표 사진 1장 삽입 (members/ 에서 해당 부스 사진 찾아서)
2. 주목기업 탭: team_vip.txt 내용을 기업별로 정리
   - 미팅 내용, 후속 조치 포함
3. 일정 탭: 기존 일정 유지 + 날짜별 대표 사진 추가
   - members/ 에서 날짜별 사진 1~2장씩 찾아서 배치
4. 최종소감 탭: "팀 종합 소감" 섹션 추가 (비워두고 [팀 소감 입력] 플레이스홀더)
5. 스플래시 스크린, 다크 테마, 탭 구조 유지
6. 단일 index.html 파일로 출력
```

#### 프롬프트 2 — 특정 섹션만 업데이트할 때

```
전시센싱 탭만 업데이트해줘.

team_notes/team_exhibition.txt 내용 기준으로:
- 같은 회사 중복 항목은 합쳐서 종합 평가 1개로 작성
- 별점 높은 순으로 정렬
- 각 회사 대표 사진 1장 (members/ 폴더에서 찾아서 삽입)
- 나머지 탭(일정/주목기업/소감)은 그대로 유지
```

#### 프롬프트 3 — 사진 갤러리 섹션 추가

```
index.html에 "팀 포토 갤러리" 탭을 추가해줘.

- 기존 탭 4개 뒤에 5번째 탭으로 추가
- members/ 폴더의 모든 사진을 날짜별 → 부스별 그리드로 배치
- 사진 클릭 시 원본 크기로 확대되는 라이트박스 효과
- 각 사진 아래에 파일명에서 추출한 설명 텍스트 표시
  (예: 홍길동_META_booth_overview.jpg → "META 부스 전경 (홍길동)")
```

#### 프롬프트 4 — 중복 부스 자동 합치기

```
team_notes/team_exhibition.txt에서 같은 회사/부스를 여러 명이 작성한 내용을 합쳐줘.

방식:
1. 회사명이 같은 블록을 찾아서
2. 각자의 관찰 내용을 "○○○ 의견:" 형식으로 합쳐서
3. 마지막에 "종합 평가:" 한 줄 자동 생성
4. 별점은 평균값으로 조정

결과를 team_notes/team_exhibition_merged.txt 로 출력해줘.
(index.html은 아직 건드리지 않음)
```

---

### D. 업로드 속도 느릴 때 대처법

팀 사진이 200장 이상이면 Antigravity 업로드가 느릴 수 있습니다.

**방법 A — 사진 압축 후 업로드**
```
Mac:
1. 사진 파일 전체 선택
2. 우클릭 → 정보 가져오기에서 용량 확인
3. 미리보기 앱 → 파일 열기 → 도구 → 크기 조절
   → 너비 1920px, 해상도 72dpi로 낮추기

Windows:
1. 사진 우클릭 → 연결 프로그램 → 그림판
2. 홈 탭 → 크기 조절 → 퍼센트 50% 적용
3. 저장 (JPEG 품질 80)
```

**방법 B — 대표 사진만 선별 업로드**
```
각 팀원에게 미리 요청:
"부스당 사진 최대 3장만 전송해주세요.
 전경 1장 + 제품 클로즈업 1장 + 기타 1장"
```

**방법 C — 메모만 먼저, 사진은 나중에**
```
1차: team_notes/ 폴더만 업로드 → 텍스트 보고서 완성
2차: 사진 폴더 추가 업로드 → "사진을 해당 섹션에 배치해줘"
```

---

### E. 역할 분담 예시 (추천)

| 역할 | 담당자 | 주요 업무 |
|------|--------|----------|
| 취합 담당자 (1명) | TBD | 파일 수집, members/ 폴더 구성, Antigravity 작업, GitHub 배포 |
| 메모 검토 (2명) | TBD | team_exhibition.txt 오탈자·누락 확인 |
| 사진 선별 (1명) | TBD | 대표 사진 1~3장/부스 선정, 파일명 검수 |
| 최종 검토 (1명) | TBD | 완성된 index.html 내용 정확성 확인 |

---

### F. 전송 요청 카카오톡 문자 템플릿 (복붙용)

```
[AWE 2026 출장보고서 자료 취합 요청]

아래 형식으로 [취합 담당자 이름]에게 6/20(금)까지 보내주세요.

📸 사진 파일명 규칙:
본인이름_부스명_설명.jpg
예) 홍길동_META_booth.jpg

📝 메모 파일:
• exhibition.txt — 센싱한 부스마다 아래 양식으로 작성:

[부스명: 회사이름] ★★★
작성자: 본인 이름
제품/기술:
핵심 특징:
- 포인트 1
- 포인트 2
인상/분석:
사진파일: 홍길동_META_booth.jpg
---

• vip_meeting.txt — 미팅 참석했으면 추가로 작성

📦 전송 방법:
사진은 카카오톡 "파일로 전송" (앨범X)
또는 구글 드라이브 공유 폴더에 업로드

❓ 문의: [취합 담당자 연락처]
```

---

## 📌 AWE 2026 주요 정보

| 항목 | 내용 |
|------|------|
| 장소 | Long Beach Convention Center, Long Beach, CA |
| 일정 | Jun 14(일) 이동 / Jun 15(월) Workshops+Welcome Party / Jun 16–17(화수) Expo Hall 11:00–17:30 / Jun 18(목) Expo 10:00–15:00 |
| 키노트 | Evan Spiegel (Snap Co-Founder & CEO) |
| 트랙 | XR & Spatial Computing / Physical AI & Robotics / Digital Twins / Immersive Video & Narrative Art |
| 규모 | 5,000+ 참가자, 250+ 전시업체, 400+ 연사 |

---

## 🔗 관련 링크

- Antigravity: https://antigravity.google
- AWE 공식 사이트: https://www.awexr.com/usa-2026
- 참고 예시 (SID 2026): https://waterfirst.github.io/sid-display-week-2026
- GitHub 가입: https://github.com/signup

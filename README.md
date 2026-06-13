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

**완성 예시 (SID 2026):** https://waterfirst.github.io/sid-display-week-2026

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

## 2단계 — 이 레포 Fork

**Fork = 나만의 복사본 만들기**

1. 이 페이지 상단 우측 **Fork** 버튼 클릭

   ```
   [Watch]  [Star]  [Fork ▼]
   ```

2. **Owner** 에서 본인 계정 선택 → **Create fork** 클릭

3. 잠시 후 `https://github.com/[내 아이디]/awe_2026_LA` 로 이동됨

> ✅ 이제 이 레포는 **내 소유**입니다. 자유롭게 수정·배포 가능.

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

## 5단계 — AI로 보고서 생성

### 5-1. 폴더 준비

포크한 레포를 로컬 PC에 다운로드:

1. 내 Fork 레포 (`github.com/[내 아이디]/awe_2026_LA`) 접속
2. **Code ▼ → Download ZIP** 클릭
3. 압축 해제 → 사진·메모 파일 넣기

완성된 폴더 구조 예시:

```
awe_2026_LA/
  ├── index.html
  ├── notes/
  │   ├── exhibition.txt    ← 현장 메모 채운 것
  │   └── vip_meeting.txt   ← 현장 메모 채운 것
  └── img/
      ├── day3/
      │   └── keynote_evan_spiegel.jpg
      ├── exhibition/
      │   ├── META_booth.jpg
      │   └── snap_spectacles.jpg
      └── vip/
          └── snap_meeting.jpg
```

### 5-2. Antigravity 업로드

1. https://antigravity.google 접속
2. **New Project** 클릭
3. `awe_2026_LA` 폴더 전체를 **드래그 앤 드롭** (또는 폴더 선택 버튼)
4. 업로드 완료 대기 (사진 양에 따라 30초~3분)

### 5-3. 프롬프트 입력 (복붙용)

아래를 **그대로 복사해서** Antigravity 채팅창에 붙여넣기:

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

> 💡 특정 탭만 업데이트하고 싶을 때:  
> "전시센싱 탭만 exhibition.txt 내용으로 업데이트해줘"

### 5-4. index.html 받기

- Antigravity가 생성한 `index.html` 파일을 **다운로드**
- 로컬 폴더의 기존 `index.html`을 **덮어쓰기**

---

## 6단계 — GitHub Pages 배포

### 6-1. 파일 업로드

**방법 A — 웹 브라우저 (추천, 가장 쉬움)**

1. 내 Fork 레포 (`github.com/[내 아이디]/awe_2026_LA`) 접속
2. `index.html` 파일 이름 클릭
3. 우측 상단 ✏️ 연필 아이콘(Edit) 클릭
4. 전체 선택(Ctrl+A) → 새 index.html 내용 붙여넣기
5. 하단 **Commit changes** 클릭 → **Commit directly to main** → 초록 확인 버튼

**방법 B — 파일 드래그 업로드**

1. 레포 메인 페이지 → **Add file ▼ → Upload files**
2. `index.html` 파일 드래그
3. **Commit changes** 클릭

**방법 C — Git CLI (개발자용)**

```bash
git clone https://github.com/[내 아이디]/awe_2026_LA.git
# 파일 수정 후
git add .
git commit -m "보고서 완성"
git push origin main
```

### 6-2. GitHub Pages 활성화 (최초 1회만)

1. 내 Fork 레포 → 상단 **⚙️ Settings** 탭
2. 왼쪽 메뉴 스크롤 → **Pages** 클릭
3. **Source** → **Deploy from a branch** 선택
4. Branch: **main** / Folder: **/ (root)** → **Save** 클릭
5. 1~3분 후 페이지 상단에 URL 표시됨:

```
🎉  Your site is live at:
    https://[내 아이디].github.io/awe_2026_LA
```

> ✅ 이후에는 파일 수정 후 커밋만 해도 URL이 자동 업데이트됩니다

---

## 🔗 팀 공유

보고서 URL을 Slack·카카오톡·이메일로 공유:

```
AWE 2026 출장 보고서 — [이름]
https://[내 아이디].github.io/awe_2026_LA
```

> 스마트폰·태블릿에서도 반응형으로 보입니다

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

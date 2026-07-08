# Bitdefender 타사 비교 페이지 — GitHub 업로드 안내

## 📦 이 폴더 구성 (이대로 올리세요)

```
index.html                          ← 비교 페이지 (메인, 반드시 루트에)
email.html                          ← 안내 이메일 (아웃룩 복붙용 / 호스팅도 가능)
support.js                          ← 페이지 구동 스크립트 (필수)
compare-data.js                     ← 115개 비교 데이터 (필수)
assets/logos/bitdefender-icon.webp  ← 헤더/푸터 아이콘 (필수)
```

> ⚠️ 5개 항목 모두 올려야 정상 동작합니다. `index.html` 은 **반드시 저장소 최상위(루트)** 에 있어야 하고, `assets/logos/` 폴더 구조도 그대로 유지해야 합니다.

---

## 🚀 업로드 방법 (웹 브라우저, 가장 쉬움)

1. **github.com** 로그인 → 오른쪽 위 **＋ → New repository**
2. **Repository name** 에 `Bitdefender-Compare` 입력
   - (이메일 버튼 링크가 `…/Bitdefender-Compare/` 로 되어 있으니 이름을 정확히 이렇게 지어야 합니다.)
3. **Public** 선택 → **Create repository**
4. 빈 저장소 화면에서 **uploading an existing file** 링크 클릭
5. 이 폴더 안의 **파일 5개 + assets 폴더를 통째로 드래그** 해서 올립니다
   - 압축(zip)은 **풀어서 내용물만** 올립니다. zip 파일째 올리면 안 됩니다.
   - 폴더(assets)를 통째로 끌어다 놓으면 `assets/logos/…` 경로가 유지됩니다.
6. 아래 **Commit changes** 버튼 클릭
7. 상단 **Settings → 좌측 Pages** 메뉴 이동
8. **Build and deployment → Source: Deploy from a branch**
   → Branch: **main** / 폴더: **/(root)** → **Save**
9. 1~2분 뒤 새로고침하면 주소가 나옵니다:
   **https://본인계정.github.io/Bitdefender-Compare/**

소개서(`Bitdefender-Intro`)와 본 페이지의 헤더·푸터·CTA 링크는 이미 서로 연결되어 있습니다.

---

## 📧 이메일을 아웃룩에 넣는 방법

1. `email.html` 을 **브라우저(크롬/엣지)** 로 엽니다
2. 본문 클릭 → **Ctrl + A**(전체 선택) → **Ctrl + C**(복사)
3. 아웃룩에서 **새 메일** 작성 → 본문에 **Ctrl + V**(붙여넣기)
4. 표·색상·막대그래프가 그대로 들어갑니다 (아웃룩 데스크톱 Word 엔진 호환 작성)

> 이미지를 쓰지 않고 표/배경색만으로 만들었기 때문에, 이미지 차단 환경에서도 레이아웃이 깨지지 않습니다.

---

## 🔁 내용 수정이 필요하면

- 비교 데이터: `compare-data.js` 안의 값만 고치면 페이지에 바로 반영됩니다.
- 그 외 디자인/문구 수정은 작업 파일(`Bitdefender-Compare.dc.html`)에서 수정 후 다시 내보내 주세요.

문의: 허성경 · admin@bluetns.co.kr · 02-595-7782

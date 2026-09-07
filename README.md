# 키친담다이 홈페이지

가스렌지가드 전문 브랜드 "키친담다이" 소개 홈페이지입니다. 기존 주남테크 사이트와 같은 디자인 포맷(블루프린트 스타일)을 사용했습니다.

## 폴더 구성 (전부 최상위에 두세요, 폴더 없이 평평한 구조)
```
index.html
style.css
script.js
about.jpg      ← 회사소개 사진 (없으면 플레이스홀더로 표시됨)
hero.jpg       ← 히어로 배경 사진 (없으면 남색 배경으로만 표시됨)
product-1.jpg  ← 가스렌지가드 제품 사진
```

## 1. 새 GitHub 저장소 만들기
1. GitHub 로그인 후 우측 상단 **+** → **New repository**
2. Repository name에 저장소 이름 입력
   - 참고: 저장소 이름은 영문으로 하는 걸 추천드려요 (예: `kitchen-damda`). 한글 "키친담다이"는 저장소 이름으로 넣으면 주소가 지저분해질 수 있어요. 화면에 보이는 브랜드명(키친담다이)은 코드 안에 이미 한글로 들어가 있으니, 저장소 이름만 영문으로 하셔도 됩니다.
3. Public 선택 → **Create repository**

## 2. 파일 업로드
1. 새로 만든 저장소 화면에서 **uploading an existing file** 클릭 (또는 Add file → Upload files)
2. 이 폴더 안의 `index.html`, `style.css`, `script.js`, 그리고 준비되면 사진 파일들을 한 번에 끌어다 놓기
3. **Commit changes**

## 3. GitHub Pages로 배포
1. 저장소 **Settings → Pages**
2. Source: `Deploy from a branch` → Branch: `main` / `/ (root)` → **Save**
3. 잠시 후 `https://사용자명.github.io/저장소명/` 주소로 접속 가능

## 아직 채워야 할 내용
- `about.jpg`, `hero.jpg`, `product-1.jpg` 사진 (지금은 비어있는 상태)
- 회사소개의 주소 / 전화 / 이메일 (지금은 예시 값)

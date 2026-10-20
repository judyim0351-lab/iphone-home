# 아이폰 홈 화면 프로토타입

## 파일 구성
- `public/index.html` — 화면 + 인터랙션 코드 전체 (HTML/CSS/JS 한 파일)
- `public/home.png` — Figma에서 내보낸 원본 홈 화면
- `public/base.png` — 아이콘을 지운 배경 (아이콘 흔들기·앱 열기 애니메이션용)

## Vercel 배포
1. 이 폴더를 GitHub 저장소에 올린 뒤 vercel.com → Add New → Project → 저장소 선택
2. Framework Preset: **Other**, Output Directory: **public** (Build Command는 비워두기)
3. Deploy

또는 터미널에서: `npx vercel` → 질문에 엔터로 진행 (Output Directory만 `public`)

## 로컬에서 보기
`npx serve public` 후 브라우저에서 열기 (파일을 더블클릭해도 동작해요)

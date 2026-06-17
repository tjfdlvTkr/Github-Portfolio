# 신준하 포트폴리오

밝은 카드형 레이아웃으로 만든 정적 포트폴리오입니다.
별도 빌드 과정 없이 GitHub 저장소에 올린 뒤 Vercel에서 바로 배포할 수 있습니다.

## 파일 구조

```text
portfolio-site/
├── index.html
├── assets/
│   ├── profile.jpeg
│   └── styles.css
└── .nojekyll
```

## 수정 위치

- 내용 수정: `index.html`
- 디자인 수정: `assets/styles.css`
- 프로필 사진 교체: `assets/profile.jpeg`

## 로컬 확인

```bash
python3 -m http.server 5173
```

브라우저에서 `http://localhost:5173`을 열어 확인합니다.

## 배포

GitHub 저장소에 push한 뒤 Vercel에서 `Github-Portfolio` 저장소를 import합니다.

- Framework Preset: `Other`
- Root Directory: `./`
- Build Command: 비워두기
- Output Directory: 비워두기 또는 `.`

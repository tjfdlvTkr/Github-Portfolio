# 신준하 포트폴리오

밝은 카드형 레이아웃으로 만든 정적 포트폴리오입니다. 별도 빌드 없이 GitHub Pages에 바로 배포할 수 있습니다.

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
- 프로필 사진 교체: `assets/profile.jpeg`를 같은 이름의 새 이미지로 바꾸면 됩니다.

## 로컬 확인

```bash
cd portfolio-site
python3 -m http.server 5173
```

브라우저에서 `http://localhost:5173`을 열어 확인합니다.

## GitHub Pages 배포

```bash
cd portfolio-site
git init
git add .
git commit -m "Create portfolio site"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

사용자 페이지 저장소 이름을 `<username>.github.io`로 만들면 배포 주소는 `https://<username>.github.io/`가 됩니다.

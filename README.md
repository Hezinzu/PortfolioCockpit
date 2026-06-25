# Portfolio Cockpit GitHub Pages Deploy

이 폴더를 GitHub 저장소 루트에 올리면 GitHub Pages로 배포할 수 있습니다.

## GitHub 웹에서 올리는 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`, `.nojekyll`, `README.md`를 업로드합니다.
3. 저장소의 `Settings > Pages`로 갑니다.
4. `Build and deployment`에서 `Source`를 `Deploy from a branch`로 선택합니다.
5. `Branch`를 `main`, 폴더를 `/(root)`로 선택하고 저장합니다.
6. 잠시 뒤 표시되는 Pages URL로 접속합니다.

## 터미널로 올리는 방법

```bash
cd /Users/HJ/Documents/Codex/2026-06-24/api-ui/outputs/github-pages
git init
git add .
git commit -m "Deploy portfolio cockpit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

그 다음 GitHub 저장소에서 `Settings > Pages > Deploy from a branch > main / root`로 설정합니다.

## 주의

GitHub Pages 사이트는 인터넷에 공개됩니다. 지금 Google Sheets는 데모용 랜덤 숫자로 바꿔둔 상태라 공유용으로 적합합니다.

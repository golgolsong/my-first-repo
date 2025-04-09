git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/golgolsong/my-first-repo.git
git push -u origin main

git remote add origin https://github.com/bokmoon/my-first-repo.git
git branch -M main
git push -u origin main

// 2025-0409

이후 파일을 고치거나 새로운 파일을 업로드 했을 때, 아래 명령어 반복

git add .
git commit -m "필요한 업데이트 이름"
git push -u origin main

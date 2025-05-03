

wget https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash


npm create vite@latest frontend -- --template react-ts
npm create vite@latest frontend -- --template react-ts
cd frontend

npm install

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

npm uninstall tailwindcss
npm cache clean --force

npx tailwindcss -i ./src/index.css -o ./dist/output.css --watch


git remote -v
git push -u origin main



git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin main


git branch --unset-upstream
git branch --set-upstream-to=origin/main main
git push -u origin main


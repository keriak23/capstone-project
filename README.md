echo "# capstone-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/keriak23/capstone-project.git
curl -sS https://webi.sh/gh | sh
gh auth login
git config user.name "Keriak23"
git config user.email "keriamerritt23@gmail.com"
git push -u origin main


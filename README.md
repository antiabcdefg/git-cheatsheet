# git-cheatsheet
git config --global user.name "antiabcdefg"  
git config --global user.email "antiabcdefg@gmail.com"  
git config --global core.ignorecase false (Enable Case Sensitive)

git init  
git add .  
git remote add origin xxx.git  
git commit -m "update"  
git branch -M main  
git push -u origin main

git push -f origin main (--force)  
git pull --rebase origin main (tip：pull = fetch + merge)

git pull xxx.git  
git checkout -b feature/xxx  
git add .  
git commit -m "fix for xxx"  
git push -u origin feature/xxx
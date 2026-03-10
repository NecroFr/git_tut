git config --global user.name "Necro"
git config --global user.email "email"
git config --global list

git init
git init -b main

git add filename
git add .

git status
git commit -m "msg"
git commit -a -m "msg"  //skip staging area

git diff
git diff --staged

git rm --cached file_address
git rm file_address

git push -u origin main
git push origin main
git push
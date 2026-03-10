git config --global user.name "Necro"<br>
git config --global user.email "email"<br>
git config --global list<br>

git init<br>
git init -b main<br>

git add filename<br>
git add .<br>

git status<br>
git commit -m "msg"<br>
git commit -a -m "msg"  //skip staging area<br>

git diff<br>
git diff --staged<br>

git rm --cached file_address<br>
git rm file_address<br>

git branch -M main //renames current branch to main<br>
git checkout -b branchname //create and switch<br>
git switch -c branchname //create and switch<br>
git switch branchname (switch/checkout)<br>
git branch<br>


git push -u origin main<br>
git push origin main<br>
git push<br>
git push origin v1.0<br>

git tag<br>
git tag -a v1.0 -m "msg"<br>
git show v1.0 (enter,space,q)<br>
git --no-pager show v1.0<br>

git log --pretty=oneline<br>
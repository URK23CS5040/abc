3RD EXPERIMENT 


git clone
ls
cd gitt-kits/
git status
---add txt file(notepad)
git status
git add -A
git status
git commit -m "adding new file"
git push origin main
clear
--to add a new branch (git checkout -b branch name(fix))
git chechout -b fix
git status
--add another line in the notepad 
git status
git add -A
git commit -m "update"
git push origin fix
git checkout main
git status
git merge fix main
git push origin main
-- add another folder and open git bash in that folder
git init
--create new repository 
git remote add origin (paste link)
git status
git add -A
git commit -m "file addition"
git push origin master
git pull origin master





git clone paste link forked acc 
cd hello
git remote-v
git remote add upstream (Mano's code)
git remote -v
clear
git fetch upstream 
git branch
git merge upstream/master 
git push origin develop



cd git kits
git submodule add link
git status
git add -A
git commit -m "submodule"
git push origin -u origin main

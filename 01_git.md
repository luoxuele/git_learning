git version
git config --global user.name "luoxuele"
git config --global user.email tianchang1994@gmail.com
git config --global -l

git config --list  
-l == --list

git help
git help config     git config --help


git init
git add 01_git.md 
git commit -m "update"

git remote add origin git@github.com:luoxuele/git_learning.git
git remote add main git@github.com:luoxuele/git_learning.git
git push -u main master

cat .git/config

git push -u main master

cd ~/.ssh
ssh-keygen -t rsa -C "tianchang1994@gmail.com"
ssh -T git@github.com



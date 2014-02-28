git
===

record some commands
--------------------------------------------



Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:promotelife/git.git
git push -u origin master

Push an existing repository from the command line
--对于已经存在的要先拉取
git pull origin master 
git remote add origin git@github.com:promotelife/git.git
git push -u origin master

-----------------------
撤销本地修改
git reset --hard origin/master 

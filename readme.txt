Git is a version controll system.
Git is free software
add can add file to repository
commit can add multifile to repository onceand 
mention some info about that
Git has a mutable index called stage
Git tracks changes of files.


Git is recording revise,if you have modify the file once,
you need to add this revise to stage(temporary storage),
then commit it to save this revise.

command:
current dir is repository dir
git init
git add filename
git commit -m infoabout
git log(view edition info) --pretty=oneline(oneline display)
git reset --hard HEAD(^+)or editionid 
git reflog(reset file log)
git status(view the working space status)
git checkout -- filename(roll back you change)
(three hava two condition:
1:you don't put it to stage,then you only use checkout
2:you have put it to stage,you not only to [git reset HEAD filename]
and do the first statu)
git rm filename git commit -m ""(delete the file) (or rm filename)
(if you not commit than you can chechout)
create a new repository on github
git remote add origin https github repository address
first time command: git push -u origin master,
then git push origin master
git clone github address

git checkout -b (branch name) create and switch to new branch
git branch (branch name) create the new branch
git checkout (branch name) switch to the branch
git branch     view the current branch
first switch to master
git merge (the branch you want to merge branch name)
git branch -d (the branch you want to delete branch name)
git log --graph view the graph of branch merge
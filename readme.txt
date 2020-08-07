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
get reset --hard HEAD(^+)or editionid 
get reflog(reset file log)
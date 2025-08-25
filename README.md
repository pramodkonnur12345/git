#for practise onl, following are some commands to remember
git init
git clone url
git log  //show logs/commit history of logs
git status
git show hashcommitvalue 

git add .  #stage for current directory
git add --A  #stage all new, modified and deleted dir in repo
git add file
git commit -m "" #commit the file
git commit -amend -m ""  #modify the file

git branch #displays the list of branch
git branch -D branchname #delete the branch
git branch -m branchname #rename the current branch

git reset #can be restored before pushing the commit
git reset --soft branchname #keeps the staged files only
git reset --mixed branchname #keeps unstaged files only
git reset --hard branchname  #discard all changes

git checkout branchname #switch to branch
git checkout -b branchname #create and switch to branch
git checkout file 3restore the file to previous content
git switch branchname # switch to branch
git switch -c branchname #create and switch to branch

git merge branch1 #merge branch1 commit to current branch
git rebase brabch1 #merge branch1 commit to the current branch, moves the current branch and replays them on top of current branch(Def only, working same but pathline changes, it mantians linear)

git fetch #fetch the branch from remote to local, but not automatically can use then and can only be view purpose, then you must use merge for working
git push # for pushing from one repo to another


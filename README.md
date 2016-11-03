# test-branch
This is a test branch

# Usage

// clone this git repository in local computer
git clone https://github.com/cloverpop/test-branch.git

// create local branch based on master branch
git checkout -b <local_branch_name> remotes/origin/master

// modify and commit
git add .
git commit -a -s 

// git upload to master
git push origin master

// add a remote branch
git push origin master:new_feature_name

// update local branch
git pull
git pull --rebase

// clean the whole local workspace
git reset --hard
git reset --hard HEAD^

// show commit
git show
git show <commit_id>

// reset entry index from staged tree to working tree. 
// No effects on working tree and current branch
git reset --q <file_name>


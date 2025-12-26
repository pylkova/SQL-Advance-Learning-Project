## git branch
git branch new_branch_name

git branch - to check list of the branch
git branch -r  - to check list of the branch of the romote repository

git branch -d new_branch_name

## git checkout
git checkout new_branch_name

git checkout -b feature/sql-windows

## git merge
1) git checkout master
2) git merge new_branch_name


Fast-forward = There were no changes in the master branch and Merge commit wasn't created

## remote branch
git push:
1)  git branch add-feature1
2) git checkout add-feature1
3) git branch
4) git push origin add-feature1

git pull origin add-feature1

git checkout add-feature1  (to create local branch and switch to this branch)

git remote show origin - to show all remote branches

git push --delete origin add-feature1

## git rebase
Option 1
1) git checkout add-feature1
2) git rebase master/main

Option 2
1) git checkout master
2) git rebase add-feature1


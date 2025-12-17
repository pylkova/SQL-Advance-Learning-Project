**git status**

**git add** - untracked -> tracked = to promote changes from the working directory to the staging area

**git add .** - stage all changes in the current directory and its subdirectories

**git commit** -m "message"

**git diff** - difference between untracked changes and the latest commit

**git diff stages** - difference between the currently tracked changes and the last commit

**git log** - commits history

**git diff COMMIT ID** - difference between the current state of the repository and the specified commit

**git reset** - *mixed* by default

**git reset HEAD ~2**

**git reset [--soft /--mixed / --hard] [commit = hash/id/head]**

hard - commits -> irrevocably delete

mixed - commits -> unstaged

soft - commits -> staged

git reset --hard HEAD ~2

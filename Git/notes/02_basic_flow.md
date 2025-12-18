## **git status**
 unstaged (utracked but saved Cmd +S) -> staged (added) -> commited

## git add
**git add** 
untracked -> tracked = to promote changes from the working directory to the staging area

**git add .**
stage all changes in the current directory and its subdirectories

## git comit
**git commit -m "meaningful message"**

**git commit -a -m**    
❗️ only for modified files ❗️ not for untracked!!!

**git commit --amend - m**
complements the last commit

## git diff

**git diff** - difference between untracked changes and the latest commit

**git diff stages**
difference between the currently tracked changes and the last commit

**git diff COMMIT ID**
difference between the current state of the repository and the specified commit

## **git log** 
commits history


## **git checkout**

### moving between *commits* 
**git checkout <hash commit #2>**

**git checkout HEAD^^**

**git checkout HEAD~2**

**git checkout master/main**

### moving between *file versions*
**git checkout <HEAD^^> -- file1 file2**

**git checkout --file 1**          
to version in HEAD  # for untracked or modified


### moving between *branches*


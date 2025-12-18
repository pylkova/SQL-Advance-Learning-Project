## **git reset**


**git reset** - *mixed* by default

**git reset HEAD ~2**

**git reset [--soft /--mixed / --hard] [commit = hash/id/head]**

hard - commits -> irrevocably delete

mixed - commits -> unstaged

soft - commits -> staged

git reset --hard HEAD ~2


 🔴 You should't delete published commits if you're working in a team!

 **git reset** can't delete untracked files

## **git clean** 
- can delete untracked files
**git clean -n** - view files that will be deleted
**git clean -f** - allow file deletion
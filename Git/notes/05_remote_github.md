## **git remote**

**git remote -v** 
view the list of repositories

**git remote add origin <url>**

## **git push** - ->
git push 
git push -u origin main/master

## **git pull** - <-
git pull origin main/master

typical mistakes:

	•	rejected
	•	diverged
	•	wrong branch

	local - remote
	add - commit

## **git clone**
to clone/download remote repository

## **SSH**
1) Find out private keys through the terminal:
**ls -al ~/.ssh** - get the list of private keys

2) Paste the private key into GitHub settings

3) Delete previous connection:
**git remote remove < name >**
git remote remove origin

4) Check:
git remote -v

5) Add new connection:
git remote add origin <SSH url from GitHub project>

6) Check:
git remote -v

7) git push --set-upstream origin main

The first time you push via SSH, GitHub is added to known_hosts.
This is normal and only happens once.
After git push --set-upstream origin main , the branch becomes tracked.

8) git branch -vv

!! If you change the remote, delete a branch, or create a new one, the upstream may disappear.
git branch -vv is a quick way to check if everything is ok.
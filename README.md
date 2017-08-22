# Git Tutorial
## Usual command
Get some commands:
- git clone
- git init
- git add
- git commit
	- git commit -m "some text"
	- git commit --amend
	- git commit --am "some text"
- git status
- git log [filename]
	- git log -p [filename]
	- git log --graph
- git reflog
- git rebase -i
- git diff
	- git diff HEAD
## Branch
- git branch
	- git branch newbranchname
	- git branch -a
- git checkout
	- git checkout -
	- git checkout branchname
	- git checkout -b newbranchname
- git merge [--no-ff] featurebranchname

## Push
- git remote add
	- git remote add origin git@github.com:username/repositoryname.git
- git push
	- git push -u origin branchname

## Learn GitHub Web

When commit something with #num, this message can be published in Issues.


# Name : Hassan Rafat Hassan 

## 1-Create a new project on your local machine then push it to your
remote repo.
sol 
1- mkdir lab2 # make folder lab2
2-cd lab2 # open folder
3- git init # mk folder git project
4- touch myscript # make file inside folder
5- vi myscript # open file and make change inside
6- git status # see any change  : myscript with red color
7-git add myscript # move file change to staging area
8-git commit -m "test file" # move file change to local repo
9- git remote add origin https://github.com/HassanRafat95/lab2task.git # create repo in my website github and take https link and make origin to push and pull file 
10- git push origin master #push file to remote repo 

## 2-create two branches (dev and test) then create two files in dev
1-git branch dev - git branch test # create branches dev and test
2-  git checkout dev # move head to dev branch 
3-git branch # see branches and any branch is active for head
4-touch dev1-touch dev2 branch 
5-git add . # . all file in folder
6-git commit -m "add dev1 and dev2 to dev branch"
7-  git push origin dev - git push origin test # push branch test and dev

## 3-merge this changes on main branch and then push it to your
remote main branch.
1-git checkout master # make head in master
2-git merge dev # merge dev branch to master
3-git push origin master # push master branch 

## 4-Tell me how to remove them locally and remotly.

git branch -d dev # delete branch locally

git push origin --delete dev
 and soon test # delete branch remotely

## 5-create an annoted tag with tagname v1.4.
git tag -a v1.4  -m "version v1.4"
git show v1.4 # show it 

## 6-push it to remote server
git push origin v1.4

## 7-tell me how to list tags locally.
 git tag 
 git tag -n # more info

## 8-tell me how to delete tag locally and remotely.
To delete a local tag
git tag -d v1.4

To delete a remote tag
git push origin --delete v1.4

## 10- What is git rebase? Give me an example
that is solution in this url
[show](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)
## 11-pull request
[show](https://git-scm.com/docs/git-request-pull)
## image 
![Image description](https://github.com/HassanRafat95/lab2task/blob/master/12.PNG)

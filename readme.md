## use the github and the git

### install git
1. you can read the URL: https://zhuanlan.zhihu.com/p/443527549
2. you also can refer the URL in CSDN. You can search "install git"
3. you should config the git config, then to show the config by the command "git config --global --list", like this.
### use git
you should config the SSH of the git, you can search how to config the SSH in Google or baidu
the step how to push a README.md file to remote
the first you should into the directory which you want to push
``` bash
# initialization the git.
1. git init
# add file to local repository, use README.md to show the step.
2. git add README.md
# commit the operation for better to query.
git commit -m "the first add"
# add remote URL for that you can push your file to the remote repository.
git remote add origin git@github.com:BlackWhite-code/xxx.git
# push your file to the remote repository.
git push -u origin master
```
``` bash
# del the file
# there are two ways to del the file
# this way do not execute the 'git add '
git rm fileName
git commit -m "delete the file."
git push origin master
# the second way to remove the file
rm -rf fileName
git add -u
git commit -m "delete the file."
git push origin master
# del the remote file in git bash
git rm --cached fileName
# del the directory in git bash
git rm -r --cached directoryName
```
``` bash
# pull the file from remote repository, the meaning of command is pull the code
# from remote origin down to local master to merge code.
git pull origin master

```
### qusetion
1. if you already add remote before, you don't add remote repository.
2. if you meet the question as the last question:
``` bash
git@github.com: Permission denied (publickey). fatal: Could not read from remote repository. Please
```
you should reset the SSH.



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
### qusetion


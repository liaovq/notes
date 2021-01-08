# git 

- origin
  - `git remote add origin <remote_path>`           add origin
  - 
- branch
  - create a branch to remote
    1. `git checkout -b <branch-name>`
    2. `git push <remote-name> <branch-name>`
    3. `git push --set-upstream <remote-name> <local-branch-name>`
  - `git push -d <remote_name> <branch_name>`       delete remote branch
  - `git merge --no-ff <branch_name>`               合并分支并禁用 Fast forward
- config
  - `git config --global user.name "name"`          修改全局name
  - `git config --global user.email "email"`        修改全局email
  - `git config user.name "name"`                   修改当前项目name
  - `git config user.name "name"`                   修改当前项目email
  - `git config --global credential.helper store`   github每次都需要输入账号密码
- remote
  - `git remote -v`                                 remote地址
- tag
  - `git push origin --tags`                        推送所有tag到远端
  - delete tag
    1. `git tag -d <version>`                       删除本地tag
    2. `git push origin :refs/tags/<version>`       删除远端tag
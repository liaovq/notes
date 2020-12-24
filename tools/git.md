# git 

- branch
  - create a remote branch
    1. `git checkout -b <branch-name>`
    2. `git push <remote-name> <branch-name>`
    3. `git push --set-upstream <remote-name> <local-branch-name>`
  - delete remote branch
    1. `git push -d <remote_name> <branch_name>`
- config
  - `git config --global user.name "name"` 修改全局name
  - `git config --global user.email "email"` 修改全局email
  - `git config user.name "name"` 修改当前项目name
  - `git config user.name "name"` 修改当前项目email
  - `git config --global credential.helper store` github每次都需要输入账号密码
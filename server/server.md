# server 

- 打开ssh远程登陆
  - `ssh` 确认是否已安装ssh client,如果未安装需要install `openssh-client`
  - `ssh localhost` 确认是否安装ssh server
  - 编辑`/etc/ssh/sshd_config` 确认是否打开`PermitRootLogin yes` `PasswordAuthentication yes`
  - `systemctl restart ssh` 重启ssh服务
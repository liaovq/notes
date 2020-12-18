# linux 

- `cat /etc/passwd` user list
- `usermod -d /home/user1 user1` add user
  - `mkdir /home/user1`
  - `chown -R user1 /home/user1` 为新用户增加权限
  - `passwd gerrit` change psw

- `userdel -Z -r -f gerry` delete user
  - -f ：删除Linux用户帐户，并强制删除文件
  - -r ：删除Linux用户帐户，包括主目录和邮件后台处理程序
  - -Z ：从Linux删除用户时，删除该用户的任何SELinux用户映射
- `whereis java`
    - `which java` java执行路径
    - `echo $JAVA_HOME`
    - `echo $PATH`
- `netstat -tunpl | grep 端口号`

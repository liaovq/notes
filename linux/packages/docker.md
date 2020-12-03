# docker  
---
### [install](https://docs.docker.com/engine/install/ubuntu/)

### command 
- 镜像仓库
    - `docker pull [OPTIONS] NAME[:TAG|@DIGEST]` 从镜像仓库中拉取
    - `docker search [OPTIONS] TERM` 从镜像仓库中查找
- 本地镜像管理
    - `docker images` 列出本地镜像。
        - `-a` 列出本地所有的镜像
        - `--digests` 显示镜像的摘要信息
- container 
    - `docker container run` 从 image 文件，生成一个正在运行的容器实例
    - `docker container start [containerID]` 启动已经生成、已经停止运行的容器文件
    - `docker container exec` 进入一个正在运行的 docker 容器
    - `docker container ls` 列出本机正在运行的容器
        - `--all` 包括终止运行的容器
        - `docker ps -a` 同上
    - `docker container stop [containerID]` 终止运行的容器文件
    - `docker container kill [containID]` 强制终止运行的容器文件，依然会占据硬盘空间
    - `docker container rm [containerID]` 删除容器文件
- compose
    - 
- `sudo apt-get purge docker-ce docker-ce-cli containerd.io` 卸载Docker Engine
- `rm -rf /var/lib/docker` 删除映像，容器，卷或自定义配置文件
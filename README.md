### docker-install.sh

**自适应docker安装脚本**

- [docker-install.sh](#docker-installsh)
  - [如何使用此脚本](#如何使用此脚本)
  - [安装内容：](#安装内容)
  - [已适配发行版：](#已适配发行版)

---

#### 如何使用此脚本

**本仓库下载：[docker-installer.sh](https://raw.githubusercontent.com/Philogag/OneKey-Docker-Install-bash/main/docker-installer.sh)**

```bash
#!/bin/sh
chmod +x ./docker-installer.sh
sudo bash ./docker-installer.sh --no-ask
```

#### 安装内容：

+ 工具：
    + curl 
    + software-properties-common 
    + apt-transport-https
    + python3-pip
+ docker
+ docker-compose

#### 已适配发行版：

+ [x] Centos 7
+ [x] Deepin 15.11
+ [x] Deepin 20 Beta
+ [x] Deepin 20
+ [x] Ubuntu 18.04
+ [x] Ubuntu 20.04
+ [ ] Debian 9
+ [ ] Debian 10

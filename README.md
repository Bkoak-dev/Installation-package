# Installation-package

#### 1.安装electron-ssr浏览器
```Bash
#!/bin/bash
#安装依赖
sudo apt install libcanberra-gtk-module libcanberra-gtk3-module gconf2 gconf-service libappindicator1 -y
sudo apt-get install libssl-dev -y
sudo apt-get install libsodium-dev -y

#安装electron-ssr
sudo dpkg -i electron-ssr-0.2.6.deb
```
批量复制导入节点，手动更新PCA

#### 2.安装Chrom浏览器
```Bash
#!/bin/bash
#使用wget下载最新的Google Chrome .deb软件包：
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
#wget https://github.com/Bkoak-dev/Installation-package/raw/main/google-chrome-stable_current_amd64.deb

#安装
sudo apt install ./google-chrome-stable_current_amd64.deb -y
google-chrome
```

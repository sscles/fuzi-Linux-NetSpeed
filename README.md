## Linux-NetSpeed 一键安装BBR原版/BBRplus版/BBR魔改版/LotServer(锐速)版内核的网络加速脚本


### 安装wget下载工具，则执行命令：
```
yum -y install wget #CentOS/RedHat
```
```
apt-get install wget #Debian/Ubuntu
```
### 执行一键安装Linux-NetSpeed网络加速脚本命令：
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/tudiedie/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
本脚本已不更新，推荐使用5.5以上内核自带的bbr速度最佳
- BBR/BBRplus/BBR2网络加速效果对比：https://roov.org/2020/03/bbr-bbrplus-bbr2/
### 如果以上脚本不能满足您的需求，您还可以使用：
```
bash <(curl -Lso- https://git.io/kernel.sh)
```

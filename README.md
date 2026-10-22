10.22日，因nodejs漏洞，以前已安装的最好更新一下：
sudo systemctl stop chicken-vps
sudo rm -f /opt/chicken-vps/vendor/node
sudo bash /opt/chicken-vps/install.sh --yes
/opt/chicken-vps/vendor/node -v
sudo systemctl status chicken-vps

让探针里的小鸡具象化到3D网页养鸡，支持大多数的ServerStatus、哪吒 （V1）、Komari、极简探针、NodeGet、
NodeFlare、CF探针里的小鸡到养鸡。

#一键安装：
```curl -fsSL https://raw.githubusercontent.com/treesky2017/chicken-vps/main/chicken-vps-20260924.run -o /tmp/cvps.run && sudo bash /tmp/cvps.run```

10.22日，因nodejs漏洞，已安装的最好更新一下：

# 停止服务
sudo systemctl stop chicken-vps
# 删除旧版私有 Node 运行时
sudo rm -f /opt/chicken-vps/vendor/node
# 重新执行安装脚本（会自动从官方拉取最新的 v22.23.4 安全版本）
sudo bash /opt/chicken-vps/install.sh --yes
# 检查当前运行的 Node 版本是否已升级
/opt/chicken-vps/vendor/node -v
sudo systemctl status chicken-vps



让探针里的小鸡具象化到3D网页养鸡，支持大多数的ServerStatus、哪吒 （V1）、Komari、极简探针、NodeGet、
NodeFlare、CF探针里的小鸡到养鸡。

#一键安装：
```curl -fsSL https://raw.githubusercontent.com/treesky2017/chicken-vps/main/chicken-vps-20260924.run -o /tmp/cvps.run && sudo bash /tmp/cvps.run```

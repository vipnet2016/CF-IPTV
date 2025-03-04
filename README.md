# CF-IPTV
# HKDVB Setup Script

这是一个用于自动化配置Nginx反代直播源并设置HKDVB港澳直播源、ofiii台湾直播的脚本，还增加了肥羊allinone直播源、iTV直播源的整理优化版本【最好保持每个部署的版本为最新版】。

## 使用方法

1. (vps)下载赋权并安装脚本：
   ```bash
   bash <(curl -sS https://fdtv.dxjc.pp.ua//setup_hkdvb.sh)

1. (openwrt)下载赋权并安装脚本：
   ```bash
   bash <(wget -qO- https://fdtv.dxjc.pp.ua/openwrtlive.sh)

如果你路由器启动不了，尝试这个代码：sh -c "$(wget -qO- https://fdtv.dxjc.pp.ua/openwrtlive.sh || curl -fsSL https://fdtv.dxjc.pp.ua/openwrtlive.sh)"

说明：肥羊allinone的默认端口：35455，同时iTV项目默认的端口是50101也才能生效


<img src="zsm.png" width="400">
感谢支持

视频支持：https://www.youtube.com/@tmxk8888

# ss-panel-v3-mod-node-connect
用于ss-panel-v3-mod面板的节点对接一键脚本，支持webapi和数据库对接

## 使用方法

先在面板中创建节点，并记住节点的id；不会的看下方链接，去看我写的原文

然后执行脚本

```shell
yum -y install wget &&
wget -N --no-check-certificate https://raw.githubusercontent.com/chen06260179/ss-panel-v3-mod-node-connect/master/ss-panel-v3-mod-node-connect.sh && 
chmod +x ss-panel-v3-mod-node-connect.sh && 
bash ss-panel-v3-mod-node-connect.sh
```

按提示选择1（webapi对接）或2（数据库对接）
然后输入相应的参数，回车执行，等待脚本安装完毕重启vps后即可成功

Linux 一键安装最新内核并开启 BBR 脚本

wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh


# Casaos_Onecloud
Casaos_玩客云搞基计划
https://github.com/muzihuaner/Casaos_Onecloud

Casaos官方
https://github.com/IceWhaleTech/CasaOS

《CasaOS—— 一个简单，易于使用，优雅的开源家庭云系统》

https://mp.weixin.qq.com/s/1oMywRTbmUADLOlSefvd9A

https://www.bilibili.com/video/BV1X94y1Z7sA?share_source=copy_web

### 安装

用SSH工具连接到你的主机
输入下面的命令

```sh
wget -qO- https://cdn.jsdelivr.net/gh/lidaokou/Casaos_Onecloud@main/script/casaos.sh | bash
```

or

```sh
curl -fsSL https://cdn.jsdelivr.net/gh/lidaokou/Casaos_Onecloud@main/script/casaos.sh | bash
```

### 卸载

v0.3.3及以上版本
```sh
casaos-uninstall
```

v0.3.3之前版本
```sh
curl -fsSL https://cdn.jsdelivr.net/gh/lidaokou/Casaos_Onecloud@main/script/casaos-uninstall.sh | bash
```

#### Docker镜像

dockerjson文件夹里是一些玩客云可以使用的镜像json文件，在应用中心-手动安装App-右上角导入

dockerjson里面的icon文件夹是自己找的图标，自定义安装的镜像有些没有图标，可将图标路径修改为

```sh
https://cdn.jsdelivr.net/gh/lidaokou/Casaos_Onecloud@main/dockerjson/icon/图标名称
```

图标名称在https://cdn.jsdelivr.net/gh/lidaokou/Casaos_Onecloud@main/dockerjson/icon/





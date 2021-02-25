# openwrt-package

请使用[基于官方openwrt源码](https://github.com/Lienol/openwrt) 和 [基于大雕源码](https://github.com/Lienol/openwrt/tree/dev-lean-lede)源码编译

使用方法：

feeds.conf.default

https://github.com/lesliedu/openwrt-packages

然后执行
```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```

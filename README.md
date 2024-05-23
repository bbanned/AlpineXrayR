# Alpine的XrayR一键安装脚本

```shell
# 安装依赖项
apk add wget unzip openrc
```

64位

```shell
wget -N https://raw.githubusercontent.com/bbanned/AlpineXrayR/main/Alpine_XrayR.sh && chmod +x Alpine_XrayR.sh && bash Alpine_XrayR.sh
```

32位

```shell
wget -N https://raw.githubusercontent.com/bbanned/AlpineXrayR/main/Alpine_XrayR_32.sh && chmod +x Alpine_XrayR_32.sh && bash Alpine_XrayR_32.sh
```

重启

```shell
/etc/init.d/XrayR restart
```

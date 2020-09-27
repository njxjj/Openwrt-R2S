#### OpenWrt原生源码+Simons的patch编译，使用前请仔细阅读如下说明：
***这是自用固件，仅有英文界面**
***如果厌烦TF上squashfs更新系统可能无法真正清除upper layer，请直接使用ext4的版本**
无意义的说明删掉了
dd写卡：
```
dd if=/tmp/upload/openwrt.img of=/dev/mmcblk0 conv=fsync
```

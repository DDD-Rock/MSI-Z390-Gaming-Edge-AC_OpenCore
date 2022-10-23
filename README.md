# MSI-Z390-Gaming-Edge-AC_OpenCore
微星 MSI Z390 Edge AC 刀锋 黑苹果OC

迫于大佬[fnoopv](https://github.com/fnoopv/MSI-Z390-Gaming-Edge-AC_OC)已停更许久，故在大佬的基础上更新OC，并作出部分调整。

友情提示：三码已抹掉，一定要记得修改三码！

目录结构：
/install/efi : 用于替换镜像安装U盘中的EFI（如果使用黑果小兵镜像刻录后直接安装，跑码显示卡在USB驱动。）
/efi : 用于安装完系统后，替换EFI分区中的引导

本人配置单：
```
主板：MSI Z390 Gaming Edge AC
CPU：i7-9700k
显卡：AMD RX6800XT 樱瞳花嫁
内存：英睿达 DDR4 4300 C17 8G*2
固态：Asgard AS2 2TB
网卡：BCM94360CD 蓝牙和wifi免驱（板载Intel无线网卡已物理卸载了）
BIOS版本：7B17vA7
```

------

# 2022-09-27 更新日志

```
1.更新OC版本至0.8.4
2.更新了Kexts驱动
3.修复由于仿造机型为MacPro7,1 从而导致无法收到Mac OS更新的问题
4.去掉了一些无效的过期配置
5.***三码已抹去，记得复用自己之前的***
6.系统版本升级至Mac OS Monterey 12.6
```



# 2022-05-05 更新日志

```
1.更新OC版本至0.8.0
2.更新了Kexts驱动
3.取消引导菜单
4.将苹果启动logo调大，显著的增强了性能[滑稽]
（如果不喜欢，可以修改uefi-显示输出-UIScale的值为1，即可在4k下变的很精致）
5.三码已抹去，记得复用自己之前的。
6.系统版本升级至Mac OS Monterey 12.3.1
```



# 2021-12-22 更新日志

本次安装镜像基于黑果小兵制作的[macOS Monterey 12.1 21C52 Installer for OC/CLOVER/PE三分区原版镜像](https://mp.weixin.qq.com/s/4JarRMfZ0KocQXAK2KRoSA)
```
1.更新OC版本至0.7.6
2.修改机型为MacPro7,1，内核扩展去掉WEG，删掉了root-args下的agdpmod=pikera
（解决HDMI和DP双显示器输出时，DP黑屏的问题）
3.引导扫描范围增加SATA硬盘（本人安装在SATA固态）
4.制作了一版安装EFI
```

---------------------------------


测试结果：
```
睡眠唤醒正常
双屏输出正常
USB定制正常
核显硬件加速正常
airpods pro自动连接正常
apple watch解锁正常
随航正常
有线网卡正常
```

---------------底线---------------

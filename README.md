# OMEN by HP Laptop 15-dc0xxx
# [解锁CFG LOCK](https://github.com/sunmousn/HP-OMEN-CFG-LOCK)
## 适用于 HP OMEN 15 的 OpenCore  
HP 暗影精灵4 配置： 
* CPU：i5 8300H & UHD630  
* 显卡：NVIDIA GeForce GTX1050Ti & 不工作已屏蔽  
* 声卡：Realtek ALC 295  
* 主板：惠普84DA & 英特尔HM370芯片组   
* 以太网卡：Realtek RTL8111  
* 无线网卡：Intel Wireless-AC 9560 & Broadcom BCM94352Z  
* 蓝牙：英特尔无线蓝牙 & Broadcom 20702A3    
* 内存：Kingston DDR4 2400MHz 8+8G  
* 硬盘：NVMe 西数 Black SN750 & SATA SGHT 1T  
 
可正常工作：  
* NVRAM  
* 摄像头  
* 以太网  
* 触控板  
* 读卡器  
* 核心显卡  
* 睡眠唤醒  
* FN组合键  
* 键盘背光灯  
* USB端口定制  
* 无线上网和蓝牙  
* 扬声器和麦克风  
* 电池信息和原生电源管理  
* Type-C转HDMI输出显示，由于HDMI音频输出跟睡眠唤醒有冲突，已禁用音频输出，如需开启请查看v4.0版本说明

注意：由于更换了Broadcom无线网卡，后发行版本不再提供intel无线网卡驱动，intel无线网卡的同学请下载v3.0版本，替换驱动如下  
AirportItlwm.kext  
IntelBluetoothFirmware.kext  
IntelBluetoothInjector.kext  
USBPorts.kext  

存在问题：  
* 亮度组合键无法使用，可通过设置快捷键F1F2来调节或者手动调节  
具体操作：系统偏好设置-键盘-快捷键-显示器 & 如果没有看到显示器选项就外接一下USB键盘就有了  
* USB端口定制修正：(v4.0版本已修正)打开Hackintool-USB-点击清除然后刷新，如连接器有USB2就将连接器里的USB2改为USB3然后导出USBPorts.kext替换即可  
<img width="1716" alt="iShot2021-10-03 15 28 52" src="https://user-images.githubusercontent.com/35004454/135744410-b5f4c3ba-7f0c-41a9-b789-8d5a554e0fd6.png">


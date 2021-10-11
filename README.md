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
* 核心显卡  
* 电池信息和原生电源管理   
* 扬声器和麦克风  
* 以太网  
* 无线上网和蓝牙  
* 摄像头  
* USB端口定制  
* Type-C转HDMI输出显示及音频
* 触控板  
* 键盘背光灯  
* 读卡器  
* FN组合键   
* NVRAM  

存在问题：  
* 亮度组合键无法使用，可通过设置快捷键F1F2来调节或者手动调节  
具体操作：系统偏好设置-键盘-快捷键-显示器 & 如果没有看到显示器选项就外接一下USB键盘就有了  
* 睡眠唤醒，具体表现为唤醒几秒钟后冻屏死机无法操作，只能强制关机  
* USB端口定制修正：打开Hackintool-USB-将连接器里的USB2改为USB3然后导出USBPorts.kext替换即可  
<img width="1716" alt="iShot2021-10-03 15 28 52" src="https://user-images.githubusercontent.com/35004454/135744410-b5f4c3ba-7f0c-41a9-b789-8d5a554e0fd6.png">


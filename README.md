# Hackintosh-MSI-MAG-B660M-Mortar-EFI

> 如果取用请生成一下序列号等信息

## 配置规格

| 部件 | 型号 |
| --- | --- |
| 主板 | 微星 B660m Motar WIFI DDR4|
| CPU | Intel Core 12700 |
| 显卡 | 蓝宝石 AMD RX580 2304sp 8G  |
| 网卡 | BCM943602CS MBP2015拆机+PCI转接板  |
| 内存 | 金百达（KINGBANK)台式机-银甲 DDR4 3200 16Gx2 |
| 硬盘M2 1 | 三星 980Pro 1T (For Windows) |
| 硬盘M2 2 | 海康威视 C2000Pro 1T (For MacOS) |


## Update

**2023-4-11**
* 增加了主题
* 增加了ReadonGPU相关Kext，用于显示GPU温度等信息
* 取消了不必要的项目
* 增加了一些kext，但未开启
> 在取消不必要项目时，注意到需要enable setupVirtualMap，否则无法启动。其实没有问题还是一般不要更新这些东西。

## BIOS Settings
#### Disable
  * **Secure Boot** [Required]
  * **Intel CFG lock** [Required]
  * Fast Boot [Optional]
#### Enable
  * USB wake up from s3/s4/s5 [Optional] used for wake up from sleep using USB HID device.
  * ERP Ready [Optional] used for wake up from sleep using USB HID device.
  * SR-IOV [Optional]

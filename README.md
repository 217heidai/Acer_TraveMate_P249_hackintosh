# Acer_TraveMate_P249_hackintosh
Install Hackintosh(Catalina 10.15.x) in Acer TraveMate P249(i5-6200U)

## 配置
* CPU: i5-6200U
* 内存: 海力士 DDR4 2133MHz 8GB
* 硬盘: 海康威视 HS-SSD-C160 512G
* 无线网卡: Intel Wireless 7265

## BIOS 配置
### 1. 重置 BIOS 为默认配置

### 2. 安装 macOS 所需配置
* BOOT
  * Secure Boot: Disabled

## 工作状态
* [x] CPU 变频、原生电源管理
* [x] 核显
* [x] 以太网
* [x] WIFI ([zxystd 大神开发的 Intel 无线网卡驱动](https://github.com/zxystd/itlwm))
* [x] 蓝牙 ([zxystd 大神开发的 Intel 蓝牙驱动](https://github.com/zxystd/IntelBluetoothFirmware))
* [x] 声卡
* [x] 摄像头
* [x] 触控板
* [x] USB 及 USB 扩展
* [x] HDMI 、VGA 输出
* [x] 关机、重启、睡眠

## 提醒

* 系统安装完, 请使用 Clover Configurator 生成 SMBIOS 序列号，否则无法登陆 App Store

## 更新日志

| 日期      | 详情                                                              |
|-----------|----------------------------------------------------------------------|
| 2020.08.13 | Clover 5120 及部分 kext 更新 |
| 2020.07.08 | Clover 5119 及部分 kext 更新 |
| 2020.06.02 | 初始版本 |
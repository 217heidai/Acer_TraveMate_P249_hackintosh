# Acer_TraveMate_P249_hackintosh
Install Hackintosh(Big Sur & Catalina) in Acer TraveMate P249(i5-6200U)

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
* [x] WIFI ([zxystd 大神开发的 Intel 无线网卡驱动](https://github.com/OpenIntelWireless/itlwm))
* [x] 蓝牙 ([zxystd 大神开发的 Intel 蓝牙驱动](https://github.com/OpenIntelWireless/IntelBluetoothFirmware))
* [x] 声卡
* [x] 摄像头
* [x] 触控板
* [x] USB 及 USB 扩展
* [x] HDMI 输出
* [x] 关机、重启、睡眠

## 提醒

* 系统安装完, 请使用 OpenCore Configurator 生成 SMBIOS 序列号，否则无法登陆 App Store

## 更新日志

| 日期      | 详情                                                              |
|-----------|----------------------------------------------------------------------|
| 2021.07.06 | OpenCroe 0.7.1 |
| 2021.06.08 | OpenCroe 0.7.0 & Big Sur 11.4 |
| 2021.05.11 | OpenCroe 0.6.9 & Big Sur 11.3 |
| 2021.04.06 | OpenCroe 0.6.8 & Big Sur 11.2.3 |
| 2021.03.03 | OpenCroe 0.6.7 & Big Sur 11.2.2 |
| 2021.02.03 | OpenCroe 0.6.6 & Big Sur 11.2 |
| 2021.01.05 | OpenCroe 0.6.5 |
| 2020.12.08 | OpenCroe 0.6.4 & Big Sur 11.1 |
| 2020.11.03 | OpenCroe 0.6.3 & Big Sur 11.0.1 RC 1 |
| 2020.10.09 | OpenCroe 0.6.2 & Big Sur 11.0 Beta 9 |
| 2020.09.21 | 迁移到 OpenCroe 0.6.2 Beta |
| 2020.08.24 | Clover 5121 |
| 2020.08.13 | Clover 5120 |
| 2020.07.08 | Clover 5119 |
| 2020.06.02 | 初始版本 |
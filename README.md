# esp32-ha-panel-fw

Waveshare ESP32-S3 Touch LCD 4B 智能家居控制面板 —— **预编译固件**。

本项目只包含刷机用的固件二进制；完整源码在私有仓库 [esp32-ha-panel](https://github.com/Andyzeng5806/esp32-ha-panel)。

## 下载

- 固件 v1.2.5（设备名超长自动换行显示）: https://github.com/Andyzeng5806/esp32-ha-panel-fw/releases/download/v1.2.5/HA_Panel.ino.bin

## 烧录说明

用 ESP32 烧录工具（esptool / 浏览器 WebSerial）把 `HA_Panel.ino.bin` 写入即可；首次开机通过面板自带的 AP 配网页填写 WiFi / MQTT。

# PhoneBatteryPlugin

手机电量显示插件。通过蓝牙连接手机后，插件会实时显示手机当前电量，方便在电脑上集中查看手机的续航状态。

## 使用前提

- 手机已通过蓝牙与电脑完成连接。
- 蓝牙连接处于正常可用状态。

## 安装

下载对应 ZIP 并解压到 TrafficMonitor 安装目录，确认以下文件位于 `plugins` 目录：

```text
plugins/PhoneBatteryPlugin.dll
```

重启 TrafficMonitor 后，在“选项 - 常规设置 - 插件管理”中启用插件。

插件项目加载后会实时更新已连接手机的电量。

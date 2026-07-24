# CursorUsagePlugin

检测 Cursor 账号额度的使用情况，并以百分比显示使用进度。通过 TrafficMonitor 可以快速查看账号当前额度的消耗情况。

## 使用前提

- 已在 Cursor 中登录需要监测的账号。
- Cursor 可以正常获取该账号的额度信息。

## 安装

下载对应 ZIP 并解压到 TrafficMonitor 安装目录，确认以下文件位于 `plugins` 目录：

```text
plugins/CursorUsagePlugin.dll
```

重启 TrafficMonitor 后，在“选项 - 常规设置 - 插件管理”中启用插件。

插件项目加载后会以百分比显示 Cursor 账号额度的使用进度。

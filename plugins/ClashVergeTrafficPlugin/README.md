# ClashVergeTrafficPlugin

检测 Clash Verge 中当前订阅的流量使用情况，并以百分比显示已用流量额度。适合将订阅流量进度直接显示在 TrafficMonitor 中，及时了解本周期的剩余额度。

## 使用前提

- Clash Verge 中存在可读取使用情况的当前订阅。
- TrafficMonitor 与 Clash Verge 均处于可正常运行状态。

## 安装

下载对应 ZIP 并解压到 TrafficMonitor 安装目录，确认以下文件位于 `plugins` 目录：

```text
plugins/ClashVergeTrafficPlugin.dll
```

重启 TrafficMonitor 后，在“选项 - 常规设置 - 插件管理”中启用插件。

插件项目加载后会以百分比反映当前订阅的流量使用进度。

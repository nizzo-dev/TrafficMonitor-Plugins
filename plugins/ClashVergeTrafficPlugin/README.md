# ClashVergeTrafficPlugin

检测 Clash Verge 中当前订阅的流量使用情况，并显示仅经过代理节点的实时上传、下载速率。

## 使用前提

- Clash Verge 中存在可读取使用情况的当前订阅。
- TrafficMonitor 与 Clash Verge 均处于可正常运行状态。

无需开启 Clash Verge 的 TCP 外部控制器；插件默认通过 `verge-mihomo` 命名管道读取连接数据，并在可用时回退到 TCP 控制端口。

## 安装

下载对应 ZIP 并解压到 TrafficMonitor 安装目录，确认以下文件位于 `plugins` 目录：

```text
plugins/ClashVergeTrafficPlugin.dll
```

重启 TrafficMonitor 后，在“选项 - 常规设置 - 插件管理”中启用插件。

插件提供三个显示项目：

- `Clash Verge用量`：当前订阅的已用流量百分比。
- `VPN上传速率`：排除 `DIRECT`、`REJECT` 后的代理上传速率。
- `VPN下载速率`：排除 `DIRECT`、`REJECT` 后的代理下载速率。

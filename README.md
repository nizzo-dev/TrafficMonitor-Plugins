# TrafficMonitor Plugins

这是一个面向 [TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor) 的独立插件集合。仓库只包含可运行的插件文件、配置和文档，不包含 TrafficMonitor 主程序、调试符号或链接产物。

## 下载

请从 [Releases](https://github.com/nizzo-dev/TrafficMonitor-Plugins/releases) 按需下载插件包。每个 ZIP 仅包含一个插件及其运行所需文件。

详细插件目录与用途见 [下载索引](download/plugin_download.md)。

## 安装

1. 下载并解压发布包。
2. 将需要的插件文件复制到 TrafficMonitor 的 `plugins` 目录。
3. 重启 TrafficMonitor。
4. 打开“选项 - 常规设置 - 插件管理”，确认插件已加载并启用。
5. 如需在任务栏显示插件项目，在任务栏窗口右键打开“显示设置”，勾选对应项目。

透明任务栏插件另有辅助 DLL，必须保留发布包内的目录结构。完整步骤见 [安装说明](docs/installation.md)。

## 插件分类

| 插件 | 分类 | 功能 | 说明与下载 |
| --- | --- | --- | --- |
| ClashVergeTrafficPlugin | 网络流量 | 读取 Clash Verge 当前订阅的流量使用情况，并以百分比显示已用额度。 | [查看](plugins/ClashVergeTrafficPlugin/README.md) |
| CursorUsagePlugin | 账号额度 | 读取 Cursor 账号的额度使用情况，并以百分比显示使用进度。 | [查看](plugins/CursorUsagePlugin/README.md) |
| MchoseKeyboardBatteryPlugin | 外设电量 | 面向迈从 K99 V3 键盘，实时显示键盘电量。 | [查看](plugins/MchoseKeyboardBatteryPlugin/README.md) |
| PhoneBatteryPlugin | 外设电量 | 通过蓝牙连接手机后，实时显示手机电量。 | [查看](plugins/PhoneBatteryPlugin/README.md) |
| T1MouseBatteryPlugin | 外设电量 | 面向泰坦精英 T1 鼠标，实时显示鼠标电量。 | [查看](plugins/T1MouseBatteryPlugin/README.md) |
| TransparentTaskbarPlugin | 系统界面 | 为 Windows 任务栏提供透明效果。 | [查看](plugins/TransparentTaskbarPlugin/README.md) |

## 更新

当前发布版本和变更记录见 [CHANGELOG.md](CHANGELOG.md)。如果将插件提交到官方插件索引，可参考 [更新指南](docs/update-guide.md) 中的 `plugins_version.xml` 说明。

## 仓库结构

```text
plugins/                 每个插件独立的二进制文件和说明
download/                下载索引
docs/                    安装、插件说明和更新指南
```

## 许可证

本仓库采用 [MIT License](LICENSE)。

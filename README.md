# TrafficMonitor Plugins

这是一个面向 [TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor) 的独立插件集合。仓库只包含可运行的插件文件、配置和文档，不包含 TrafficMonitor 主程序、调试符号或链接产物。

## 下载

请从 [Releases](https://github.com/nizzo-dev/TrafficMonitor-Plugins/releases) 下载发布包。每个发布包均包含适用于 TrafficMonitor x64 Lite 的全部插件。

详细插件目录与用途见 [下载索引](download/plugin_download.md)。

## 安装

1. 下载并解压发布包。
2. 将需要的插件文件复制到 TrafficMonitor 的 `plugins` 目录。
3. 重启 TrafficMonitor。
4. 打开“选项 - 常规设置 - 插件管理”，确认插件已加载并启用。
5. 如需在任务栏显示插件项目，在任务栏窗口右键打开“显示设置”，勾选对应项目。

透明任务栏插件另有辅助 DLL，必须保留发布包内的目录结构。完整步骤见 [安装说明](docs/installation.md)。

## 插件分类

| 分类 | 插件 |
| --- | --- |
| 网络流量 | ClashVergeTrafficPlugin |
| 外设状态 | CursorUsagePlugin、MchoseKeyboardBatteryPlugin、PhoneBatteryPlugin、T1MouseBatteryPlugin |
| 系统界面 | TransparentTaskbarPlugin |

## 更新

当前发布版本和变更记录见 [CHANGELOG.md](CHANGELOG.md)。如果将插件提交到官方插件索引，可参考 [更新指南](docs/update-guide.md) 中的 `plugins_version.xml` 说明。

## 仓库结构

```text
network/                 网络流量插件
peripherals/             键盘、鼠标、手机和光标相关插件
system-ui/               系统外观插件及其依赖
download/                下载索引
docs/                    安装、插件说明和更新指南
```

## 许可证

本仓库采用 [MIT License](LICENSE)。

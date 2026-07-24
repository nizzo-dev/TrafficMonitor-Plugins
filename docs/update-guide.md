# 更新指南

## 发布个人仓库更新

1. 更新插件二进制文件和对应文档。
2. 更新 [CHANGELOG.md](../CHANGELOG.md)。
3. 创建 Git 标签，例如 `v1.0.1`。
4. 创建同名 GitHub Release，并上传完整 ZIP 发布包。

## 官方插件索引更新

TrafficMonitor 的官方插件索引仓库使用 `plugins_version.xml` 为“插件管理”界面提供更新提示。个人仓库中的 Release 不会自动出现在该界面。

若希望接入官方更新提示，需要向 [zhongyang219/TrafficMonitorPlugins](https://github.com/zhongyang219/TrafficMonitorPlugins) 提交插件介绍、下载链接，以及更新后的 `plugins_version.xml`。每次发布新版本时，都应同步更新对应插件的版本号和下载地址。

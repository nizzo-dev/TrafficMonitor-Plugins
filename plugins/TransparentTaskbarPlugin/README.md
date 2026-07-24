# TransparentTaskbarPlugin

为 Windows 任务栏提供透明效果，使任务栏视觉上更加简洁，并与桌面背景融合。

## 功能说明

插件通过 `TransparentTaskbarPlugin.ini` 保存运行设置，并依赖 `TaskbarAccentHook.dll` 提供任务栏外观处理。因此三个文件都必须保留在发布包指定的位置。

## 安装

下载对应 ZIP 并解压到 TrafficMonitor 安装目录。必须保留以下完整结构：

```text
plugins/
  TransparentTaskbarPlugin.dll
  TransparentTaskbarPlugin.ini
  TransparentTaskbarPlugin/
    TaskbarAccentHook.dll
```

重启 TrafficMonitor 后，在“选项 - 常规设置 - 插件管理”中启用插件。`TransparentTaskbarPlugin.ini` 用于保存运行设置，应与插件 DLL 放在同一目录。

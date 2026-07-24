# 安装说明

## 前提条件

- 使用 x64 版 TrafficMonitor Lite。
- Windows 10 或更高版本。
- 安装前先退出 TrafficMonitor，避免 DLL 被占用。

## 常规插件

将每个插件 DLL 复制到 TrafficMonitor 的 `plugins` 目录：

```text
TrafficMonitor/
  plugins/
    PluginName.dll
```

复制完成后重新启动 TrafficMonitor，在“选项 - 常规设置 - 插件管理”中确认插件被加载。

如需将插件项目显示到任务栏，在任务栏窗口右键打开“显示设置”，勾选需要显示的项目后保存。

## TransparentTaskbarPlugin

该插件包含辅助 DLL，安装时必须保留以下结构：

```text
TrafficMonitor/
  plugins/
    TransparentTaskbarPlugin.dll
    TransparentTaskbarPlugin.ini
    TransparentTaskbarPlugin/
      TaskbarAccentHook.dll
```

`TransparentTaskbarPlugin.ini` 保存插件运行设置，必须与插件 DLL 放在同一目录。

## 升级

替换 DLL 前关闭 TrafficMonitor。除非新版本明确说明配置格式有变化，否则请保留已有的插件 INI 文件。

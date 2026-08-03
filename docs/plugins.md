# 插件说明

每个插件的安装包、依赖和单独使用说明均位于 `plugins/<插件名>/README.md`。本页仅保留总览。

## 网络流量

### ClashVergeTrafficPlugin

显示 Clash Verge 当前订阅用量，以及排除 `DIRECT`、`REJECT` 后仅经过代理节点的实时上传、下载速率。默认通过 Clash Verge 的 `verge-mihomo` 命名管道读取，无需开启 TCP 外部控制器。

所需文件：

```text
plugins/ClashVergeTrafficPlugin/ClashVergeTrafficPlugin.dll
```

## 外设状态

### CursorUsagePlugin

检测 Cursor 账号额度的使用情况，并以百分比显示使用进度。

所需文件：

```text
plugins/CursorUsagePlugin/CursorUsagePlugin.dll
```

### MchoseKeyboardBatteryPlugin

主要面向迈从 K99 V3 键盘，实时显示键盘电量。

所需文件：

```text
plugins/MchoseKeyboardBatteryPlugin/MchoseKeyboardBatteryPlugin.dll
```

### PhoneBatteryPlugin

通过蓝牙连接手机后，实时显示手机电量。

所需文件：

```text
plugins/PhoneBatteryPlugin/PhoneBatteryPlugin.dll
```

### T1MouseBatteryPlugin

主要面向泰坦精英 T1 鼠标，实时显示鼠标电量。

所需文件：

```text
plugins/T1MouseBatteryPlugin/T1MouseBatteryPlugin.dll
```

## 系统界面

### TransparentTaskbarPlugin

为 Windows 任务栏提供透明效果。该插件需要同级 INI 文件和辅助 DLL。

所需文件：

```text
plugins/TransparentTaskbarPlugin/TransparentTaskbarPlugin.dll
plugins/TransparentTaskbarPlugin/TransparentTaskbarPlugin.ini
plugins/TransparentTaskbarPlugin/TaskbarAccentHook.dll
```

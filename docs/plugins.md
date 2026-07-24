# 插件说明

每个插件的安装包、依赖和单独使用说明均位于 `plugins/<插件名>/README.md`。本页仅保留总览。

## 网络流量

### ClashVergeTrafficPlugin

为 Clash Verge 提供流量相关信息。

所需文件：

```text
plugins/ClashVergeTrafficPlugin/ClashVergeTrafficPlugin.dll
```

## 外设状态

### CursorUsagePlugin

提供光标使用相关信息。

所需文件：

```text
plugins/CursorUsagePlugin/CursorUsagePlugin.dll
```

### MchoseKeyboardBatteryPlugin

为支持的 MCHOSE 键盘提供电量信息。

所需文件：

```text
plugins/MchoseKeyboardBatteryPlugin/MchoseKeyboardBatteryPlugin.dll
```

### PhoneBatteryPlugin

为已连接手机提供电量信息。

所需文件：

```text
plugins/PhoneBatteryPlugin/PhoneBatteryPlugin.dll
```

### T1MouseBatteryPlugin

为支持的 T1 鼠标提供电量信息。

所需文件：

```text
plugins/T1MouseBatteryPlugin/T1MouseBatteryPlugin.dll
```

## 系统界面

### TransparentTaskbarPlugin

控制任务栏透明效果。该插件需要同级 INI 文件和辅助 DLL。

所需文件：

```text
plugins/TransparentTaskbarPlugin/TransparentTaskbarPlugin.dll
plugins/TransparentTaskbarPlugin/TransparentTaskbarPlugin.ini
plugins/TransparentTaskbarPlugin/TaskbarAccentHook.dll
```

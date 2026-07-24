# Installation

## Standard Plugins

Copy each plugin DLL into TrafficMonitor's `plugins` directory:

```text
TrafficMonitor/
  plugins/
    PluginName.dll
```

Restart TrafficMonitor after copying the plugin.

## TransparentTaskbarPlugin

This plugin has an additional helper DLL. Preserve this layout when installing it:

```text
TrafficMonitor/
  plugins/
    TransparentTaskbarPlugin.dll
    TransparentTaskbarPlugin.ini
    TransparentTaskbarPlugin/
      TaskbarAccentHook.dll
```

`TransparentTaskbarPlugin.ini` contains the plugin's runtime settings. Keep it alongside the plugin DLL.

## Upgrade

Close TrafficMonitor before replacing a plugin DLL. Preserve plugin INI files unless the new release documents a configuration change.

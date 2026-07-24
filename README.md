# TrafficMonitor Plugins

Independent plugins for [TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor).

This repository contains release-ready plugin files grouped by purpose. It does not include TrafficMonitor itself, debug symbols, import libraries, or other build artifacts.

## Requirements

- TrafficMonitor x64 Lite release
- Windows 10 or later, unless a plugin specifies otherwise

## Installation

1. Download the plugin files from the latest release.
2. Copy the files for the desired plugin into TrafficMonitor's `plugins` directory.
3. Restart TrafficMonitor.

For the full layout and plugin-specific notes, see [docs/installation.md](docs/installation.md) and [docs/plugins.md](docs/plugins.md).

## Plugin Categories

| Category | Plugins |
| --- | --- |
| Network traffic | ClashVergeTrafficPlugin |
| Peripheral status | CursorUsagePlugin, MchoseKeyboardBatteryPlugin, PhoneBatteryPlugin, T1MouseBatteryPlugin |
| System UI | TransparentTaskbarPlugin |

## Repository Layout

```text
network/                 Network-traffic plugins
peripherals/             Keyboard, mouse, phone, and cursor plugins
system-ui/               System appearance plugins and dependencies
docs/                    Installation and plugin reference
```

## License

No license has been selected yet. Do not redistribute or modify these plugins until a license is added.

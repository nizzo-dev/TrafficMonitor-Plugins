# Changelog

All notable changes to this plugin collection are documented here.

## v1.0.0 - 2026-07-24

- First public release of the TrafficMonitor plugin collection.
- Added network, peripheral-status, and system-UI plugin categories.
- Added Chinese installation, download, plugin-reference, and update documentation.

## v1.0.1 - 2026-07-24

- Reorganized the repository so every plugin has its own directory and README.
- Changed releases from one combined archive to individual plugin ZIP files.

## v1.0.2 - 2026-07-24

- Expanded the functional description and intended-device information for every plugin.

## v1.0.3 - 2026-08-03

- Added live proxy-only upload and download rates to ClashVergeTrafficPlugin.
- Added direct Clash Verge `verge-mihomo` named-pipe support without requiring the TCP external controller.

## v1.0.4 - 2026-10-14

- ClashVergeTrafficPlugin: discover Clash Verge 2.5.4 `verge-mihomo-production-<hash>` pipes when the legacy pipe is unavailable; fall back to TCP only when the controller is listening.
- ClashVergeTrafficPlugin: yellow/red speed badges above 512 KB/s and 1 MB/s.
- CursorUsagePlugin: show total tokens used in the current billing cycle on hover and in plugin options.

## Usage

View paired Bluetooth devices via the `btl` keyword. Type to filter by device name.

![View devices](images/btl.png)

* <kbd>↩</kbd> Connect or disconnect the selected device.
* <kbd>⌥</kbd><kbd>↩</kbd> Star or unstar a device.
* <kbd>⌘</kbd><kbd>↩</kbd> Hide the selected device from the list.
* <kbd>⌃</kbd><kbd>↩</kbd> Unpair the selected device.

Turn Bluetooth on and off with the `bton` and `btoff` keywords, or toggle it with `btt`. All keywords are configurable in the Workflow’s Configuration.

![Turn Bluetooth on](images/bton.png)

![Turn Bluetooth off](images/btoff.png)

Copy a diagnostics report to include in a bug report with the `btdiag` keyword. Hold <kbd>⌥</kbd> to copy a version without device names.

Bluetooth LE devices are marked `(BLE)` in the list. macOS does not allow third-party apps to disconnect them, such as the Logitech MX Master 3S or Keychron K3 Max; use Control Center to disconnect those.

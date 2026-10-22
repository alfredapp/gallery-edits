## Usage

View paired bluetooth devices via the `btl` keyword. Press <kbd>↩</kbd> to connect and disconnect, <kbd>⌥</kbd><kbd>↩</kbd> to star a favorite and <kbd>⌘</kbd><kbd>↩</kbd> to hide a device from the list.

![View devices](images/btl.png)

Type to filter the list by device name.

![Filter devices](images/btl-filter.png)

Hold <kbd>⌃</kbd> and press <kbd>↩</kbd> to unpair a device (experimental, asks for confirmation).

Turn bluetooth on and off with the `bton` and `btoff` keywords, or toggle it with `btt`. All keywords are configurable in the workflow settings.

![Turn bluetooth on](images/bton.png)

![Turn bluetooth off](images/btoff.png)

Copy a diagnostics report to include in a bug report with the `btdiag` keyword. Hold <kbd>⌥</kbd> to copy a version without device names.

Note that macOS does not allow third-party apps to disconnect Bluetooth LE devices, such as the Logitech MX Master 3S or Keychron K3 Max. Use Control Center to disconnect those.

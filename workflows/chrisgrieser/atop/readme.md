## Usage

List all available tools via `atop`. The most frequently used have their own configurable keywords.

![Listing all tools](images/atop.png)

### Processes

Search running processes with the `top` keyword.

![Searching running processes](images/top.png)

* <kbd>↩</kbd> Kill the process.
* <kbd>⌘</kbd><kbd>↩</kbd> Force kill the process.
* <kbd>⌃</kbd><kbd>↩</kbd> Kill all processes with the same name.
* <kbd>⌘</kbd><kbd>⌃</kbd><kbd>↩</kbd> Force kill all processes with the same name.
* <kbd>⇧</kbd><kbd>↩</kbd> If the process belongs to a regular app, restart it.
* <kbd>⌥</kbd><kbd>↩</kbd> Copy process ID.

#### Icon legend

* `⭕` indicates that the process is owned by root.
* `n⇣` means that the process is a parent of `n` child processes.
* `↖ foobar` indicates that the process is a child of `foobar`.

### Bluetooth

Search paired bluetooth devices with the `blue` keyword.

![Searching paired bluetooth devices](images/blue.png)

* <kbd>↩</kbd> Toggle connection if [`blueutil`](https://formulae.brew.sh/formula/blueutil) is installed. Otherwise, open bluetooth in System Preferences.
* <kbd>⌥</kbd><kbd>↩</kbd> Copy device address.

### Removable Volumes

Search mounted volumes via the `vol` keyword.

![Searching mounted volumes](images/vol.png)

* <kbd>↩</kbd> Open the Volume in the Finder.
* <kbd>⌘</kbd><kbd>↩</kbd> Browse the Volume in terminal.
* <kbd>⌃</kbd><kbd>↩</kbd> Eject Volume.

### DNS

Change DNS servers via the `dns` keyword.

![Showing DNS servers](images/dns.png)

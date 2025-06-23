## Setup

[Install the 1Password CLI](https://1password.com/downloads/command-line/) and turn on the integration in 1Password Preferences → Developer → Connect with 1Password CLI.

![1Password preferences](images/1password_preferences.png)

## Usage

Interact with your 1Password items via the `1p` keyword.

![Alfred search for 1p](images/1p.png)

* <kbd>↩</kbd> Open and Fill.
* <kbd>⌘</kbd><kbd>↩</kbd> View in 1Password.
* <kbd>⌥</kbd><kbd>↩</kbd> Copy Username.
* <kbd>⌃</kbd><kbd>↩</kbd> Copy Password.
* <kbd>⇧</kbd><kbd>↩</kbd> Copy One-Time Password

Uncommon but useful actions, such as toggling vaults, can be accessed with `:1pextras`.

![Alfred search for :1pextras](images/1pextras.png)

![Results for managing vaults](images/vaults.png)

A Fallback Search is included.

To report a problem, run `!1pdiagnostic`.

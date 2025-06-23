## Setup

Set up `pass` with a GPG key, as per [the instructions](https://www.passwordstore.org/) on the `pass` website. Then Configure `pinentry-mac` as your pinentry program:

```
   [[ -d "$HOME/.gnupg" ]] || mkdir "$HOME/.gnupg"
echo "pinentry-program $(brew --prefix)/bin/pinentry-mac" > $HOME/.gnupg/gpg-agent.conf
gpgconf --kill gpg-agent # restart the agent
```

## Usage

Search your passwords via the `pw` keyword.

![Searching passwords](images/pw.png)

* <kbd>↩</kbd> Copy password to the clipboard.
* <kbd>⌘</kbd><kbd>↩</kbd> Edit entry in terminal.
* <kbd>⌥</kbd><kbd>↩</kbd> Reveal `.gpg` file of the entry in Finder.
* <kbd>⌃</kbd><kbd>↩</kbd> Delete entry.
* <kbd>⇧</kbd><kbd>↩</kbd> Show entry details. Select any to copy the value to the clipboard.
* <kbd>fn</kbd><kbd>↩</kbd> Generate a new password, update the entry, and copy the new password.

Create a new entry via the `pw new` keyword. If your search query does not find an entry, you can directly create a new one by pressing <kbd>↩</kbd>. You are then prompted for a folder to place the new entry in. The password of the new entry is auto-generated based on your `pass` settings, or can be inserted from your clipboard.

![Create a new entry](images/pwnew.png)

Generate a new password without creating a new entry with the `pw gen` keyword. This can be useful to change an existing password.

![Generate a new password](images/pwgen.png)

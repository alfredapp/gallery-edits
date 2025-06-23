## Usage

Run shell commands without opening a terminal via the `cmd` keyword. Your shell’s configuration files will be loaded, making your custom aliases, functions, and more available to the environment. Commands execute relative to the frontmost Finder window to allow quick changes on the current working folder. Exit status is shown as a notification and output in a Text View.

![Sending command](images/cmd.png)

* <kbd>↩</kbd> Run the command.
* <kbd>⌘</kbd><kbd>↩</kbd> Run command but do not open output in Text View.
* <kbd>⌥</kbd><kbd>↩</kbd> Show command history to rerun a command.

Use the Universal Action to send files and text as arguments to a command. If the placeholder from the Workflow’s Configuration is present in the text, it will be replaced with your arguments, otherwise they are appended to the end.

![Universal Action selecting files](images/ua.png)

![Universal Action command](images/uacommand.png)

The same modifiers apply. Separate command histories are created for commands ran with the Keyword or the Universal Action.

![Command history](images/history.png)

* <kbd>↩</kbd> Run command.
* <kbd>⌘</kbd><kbd>↩</kbd> Delete all command histories and saved outputs.
* <kbd>⌘</kbd><kbd>Y</kbd> Quick Look saved output.

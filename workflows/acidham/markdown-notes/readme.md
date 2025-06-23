## Setup

Set the location of your markdown files folder and your markdown editor and viewer apps in the Workflow’s Configuration.

## Usage

Search the contents of markdown files via the `mds` keyword. `&`, `|`, and `*` help refine your search:

* `wood table` Search for exact phrase.
* `wood&table` Search for both words.
* `wood|table` Search for either word.
* `tab*` Search for words starting with `tab`.

![Searching files](images/mds.png)

Search for task list items with the `mdt` keyword.

![Searching tasks](images/mdt.png)

In both cases, <kbd>↩</kbd> opens the file in your markdown editor and <kbd>⌘</kbd><kbd>↩</kbd> reveals more actions.

![Action note](images/actions.png)

Further options are available with the Universal Actions.

![Universal actions for markdown notes](images/ua.png)

Search tags with the `md#` keyword. Tags can be added to files with simple syntax:

```
Tags: #work #ideas
```

![Searching tags](images/tags.png)

If a tag matches the configured Bookmark Tag keyword, the URLs from that file will be displayed with the `mdb` keyword.

![Searching URLs](images/mdb.png)

Create new notes via `mdc`. Give a title optionally followed by tags.

![Creating new note](images/mdc.png)

## Setup

Reveal the Helper app in the Finder via the `:mangahelper` keyword. This is enough for make macOS to become aware of it and set an identifier for CBZ files.

![Show helper app in Finder](images/helper.png)

You can associate CBZ files with the app so they open in Alfred by default.

## Usage

Read Manga and Comic Books via the Universal Action. Supported formats include CBZ, ZIP, and PDF.

![Universal Action to initiate reading](images/ua.png)

![Reading pages](images/reading.png)

* <kbd>←</kbd> Previous page.
* <kbd>→</kbd> Next page.
* <kbd>↩</kbd> Save current position and exit.
* <kbd>⌘</kbd><kbd>↩</kbd> Restart from beginning.

When rerunning the Universal Action on the same file in the same location, pages prior to the last saved position are excluded. To reinclude all pages and start from the beginning, use the Universal Action with <kbd>⌘</kbd><kbd>↩</kbd>.

Merge different chapters into a single file via the `Merge Chapters` Universal Action.

![Universal Action to merge chapters](images/merge.png)

## Setup

Set your Google Drive’s location in the Workflow’s Configuration.

## Usage

Search the contents of your Google Drive via the `gd` keyword. Filter for folders only with `gdf`. Fallback Searches are included.

![Alfred search for gd](images/gd.png)

![Alfred search for gd fran](images/gdfran.png)

* <kbd>↩</kbd> Open.
* <kbd>⌥</kbd><kbd>↩</kbd> Reveal in Finder.
* <kbd>⇧</kbd><kbd>↩</kbd> Search on Google Drive’s website.

You’ll be asked to build the cache on the first run. A notification will show when it’s ready. The more files you have, the longer the wait. A macOS launchd agent will be loaded to do it daily. An immediate cache rebuild can be forced with <kbd>⌘</kbd><kbd>⌥</kbd><kbd>⌃</kbd><kbd>↩</kbd>.

The Universal Actions make it straightforward to copy and move files to a Google Drive folder.

![File Actions for Google Drive copy and mode](images/fileaction.png)

To report a problem, run `!gddiagnostic`.

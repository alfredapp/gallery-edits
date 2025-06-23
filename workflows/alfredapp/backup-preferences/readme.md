## Usage

Generate a backup of your local Alfred Preferences via the `start backup` keyword. A macOS launchd agent will be loaded to do it daily at the time set in the Workflow’s Configuration (using the [24-hour clock format](https://en.wikipedia.org/wiki/24-hour_clock)). The number of versions to keep is likewise configurable.

![Starting a backup](images/start.png)

Restore a previous version with the `restore backup` keyword. It takes a few seconds to complete and restarts Alfred.

![Listing backups to restore](images/restore.png)

## Usage

Add and search for links in [GoodLinks](https://goodlinks.app).

### Add URL to GoodLinks

Add the URL of the frontmost browser's active tab to GoodLinks via the `glb` keyword.

![glb keyword](images/glb-keyword.png)

Add any link to GoodLinks via the Universal Action.

![url add universal action](images/add-url-universal-action.png)

#### Add URL Modifier Keys

* <kbd>↩︎</kbd> Add URL to GoodLinks
* <kbd>⌥</kbd><kbd>↩︎</kbd> Add URL and edit info (tags, etc.) in GoodLinks

### Search GoodLinks

Search all links via the `gla` keyword.

![gla keyword](images/gla-keyword.png)

Search unread links via the `glu` keyword.

![glu keyword](images/glu-keyword.png)

Search for a random unread link via the `gl?` keyword, with the option to search again.

![gl? keyword](images/gl-question-mark-keyword.png)

Search starred links via the `gls` keyword.

![gls keyword](images/gls-keyword.png)

Search for a tag via the `glt` keyword.

![glt keyword](images/glt-keyword.png)

To get links with a specific tag, action the result, or enter a tag name via the `glwt` keyword.

![glwt keyword](images/glwt-keyword.png)

#### Search Modifier Keys

* <kbd>↩︎</kbd> Open the link in GoodLinks
* <kbd>⌥</kbd><kbd>↩︎</kbd> Copy the link to the clipboard.
* <kbd>⌘</kbd> View the link's starred status,read/unread status, and tags, if any. (These defaults can be switched in the workflow's Configuration.)
* <kbd>⌃</kbd> Show the link's URL
* <kbd>⌘</kbd><kbd>L</kbd> Use Alfred's [Large Type](https://www.alfredapp.com/help/features/large-type/) feature to show a large-type view of the link's title, and if available, summary.

### Cached Workflow Data

Delete the workflow's caches via the `:glflush` keyword.

![:glflush keyword](images/glflush-keyword.png)

Afterwards, adding a URL or invoking a search will rebuild the cache with updated data from GoodLinks.

By default, the workflow caches GoodLinks data for 3600 seconds (1 hour), using a combination of Alfred's built-in script-filter cacheing and a cache file. The caches are rebuilt any time a URL is added via this workflow, or when initiating a search on an expired cache.

## Configuration

The workflow provides configuration for default search subtext, keywords, and cache duration.

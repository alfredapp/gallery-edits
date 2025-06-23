## Setup

Set the Base URL and API Token of your [Mealie](https://github.com/mealie-recipes/mealie/) installation in the Workflow’s Configuration. You can generate an API Token from your Mealie user profile under API Tokens.

## Usage

Search for your [Mealie](https://mealie.io/) recipes via the `mealie` keyword.

![Searching for Mealie recipes](images/keyword.png)

Type to refine your search. Recipes are always filtered by title, while filtering by description, categories, tags, and tools is configurable from the Workflow’s Configuration.

![Narrowing search for Mealie recipes](images/filter.png)

* <kbd>↩</kbd> Open recipe in Alfred.
* <kbd>⌘</kbd><kbd>↩</kbd> Open recipe in browser.
* <kbd>⌃</kbd><kbd>↩</kbd> Delete recipe from Mealie.

Recipes can be viewed directly within Alfred. This includes a list of Prep Times, Ingredients, Required Tools, Step-by-Step Instructions, and Notes.

![Viewing Mealie Recipe](images/recipeview.png)

* <kbd>⌘</kbd><kbd>↩</kbd> Open recipe in browser.
* <kbd>⌥</kbd><kbd>↩</kbd> Refresh recipe data.

Append `::` to the configured keyword to access other actions, including manually reloading the recipes cache.

![Other actions](images/inlinesettings.png)

Recipe auto-updating is supported. The main recipe list auto-updates based on the slider in the Workflow's Configuration, while individual recipes refresh automatically based on data from the main recipe list.

Configure the Hotkey as a shortcut to search for your recipes. Use the Universal Action to add URLs to Mealie from selected text or Alfred’s Clipboard History.

![Using the Universal Action](images/ua.png)

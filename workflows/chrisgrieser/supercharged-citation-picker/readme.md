## Setup

Set your BibTeX Library location in the Workflow’s Configuration.

## Usage

Start the citation picker via the `ct` keyword. You can search for the title, author/editor (last name), year, collection, or journal name. Configure the Hotkey for faster triggering.

![Searching citations](images/ct.png)

### Search

* You can search for the title, author/editor (last name), year, collection, or journal name.
* Prepend `@` to a word to search for a citekey, for example `@Grieser2020`.
* Prepend `#` to search for keywords (tags), for example `#sociology`.
* Search for any combination of the above. For example, the query `2020 #cognition grieser` searches for entries published in 2020, with the tag `cognition` and `Grieser` as author/editor.

### Citation Actions

* <kbd>↩</kbd> Paste the citekey of the selected citation.
* <kbd>⌥</kbd><kbd>↩</kbd> Add another citation.
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>↵</kbd> Paste an inline-citation (e.g. `@Grieser2022` instead of `[@Grieser2022]`).
* <kbd>⌘</kbd><kbd>↩</kbd> Add page numbers before pasting the selected citekey.
  * Confirm the page number with <kbd>⌥</kbd><kbd>↩</kbd> (or <kbd>⌘</kbd><kbd>↩</kbd>) to add another citation afterward.
  * Confirm with <kbd>⇧</kbd><kbd>⌘</kbd><kbd>↩</kbd> for an inline-citation with page number (`@Grieser2022 [p. 42]`).

### URL Actions

* <kbd>⌃</kbd><kbd>↩</kbd> Open the URL in the browser.
* <kbd>⌘</kbd><kbd>C</kbd> Copy the URL to the clipboard.

In both cases, if the entry has a DOI but not a URL, the citation picker uses the DOI-URL (`https://doi.org/…`) instead.

### Additional Features

* Inserts **Pandoc Citation Syntax** (`[@citekey]`), supporting page numbers and multiple citations (`[@citekey, p. 23; @citekey, p. 42]`). Can also be configured to use **LaTeX**, **Multi-Markdown**, **eta templates**, **Org Mode**, `[[wikilinks]]`, `#tags` or `bare citkeys` as citation format.
* Paste single-entry bibliographies, open URLs, open or create literature notes, attach PDFs, search for `.csl` files online, and more.
* **Lightweight Reference Manager:** Automatically rename and file PDFs, remove, entries, and more.
* **Quickly Add New Entries:** Select a DOI or ISBN and add them directly to your BibTeX library via hotkey.
* **Obsidian Integration:** When located in your [Obsidian](https://obsidian.md/) Vault, literature notes are automatically opened or created in Obsidian instead of the default markdown app.

# Workflow Submit Form Checkbox Clarifications

Expanded information for the [Workflow Submission form](https://github.com/alfredapp/gallery-edits/issues/new?template=01_submit_workflow.yml) checkboxes.

### Authorship

Workflows must be submitted by their authors.

### Configuration

If the workflow has user-facing settings, they must use [Workflow Configuration](https://www.alfredapp.com/help/workflows/user-configuration/) functionality and *not* Workflow Environment Variables.

### Auto-updating

 Workflows available in the Gallery are updatable from Alfred. Workflows must not update themselves to not cause conflicts.

### Signed Binaries

Workflows must not have unsigned and non-notarised binaries, or otherwise try to bypass this macOS security feature (e.g. by removing quarantine). Scripts don’t fall into this category.

### Downloading Software

Every bit of executable code must be contained in the workflow. The workflow should never install extra software itself, including (but not limited to) running `pip install`, `gem install`, `brew install`, or `curl`ing a binary.

Bundling libraries with the workflow is accepted. For Homebrew installations, list them in the form and [Alfred will handle them](https://www.alfredapp.com/help/kb/dependencies/).

### Short Keywords

Keywords which are too short can get lost amongst user results or conflict with other workflows. While there are rare exceptions, workflow keywords (including in Script Filters, File Filters, or similar) should in general be at least three characters long. Ideally they will also be [user-configurable](https://www.alfredapp.com/help/workflows/advanced/keywords/#configurable).

### About Section

Workflows should have instructions in the [About](https://www.alfredapp.com/help/workflows/advanced/sharing-workflows/#about), to help new users. See the [Gallery Style Guide](https://github.com/alfredapp/gallery-edits/blob/main/Documentation/Workflow%20Page%20Style%20Guide.md) to learn the format used in Gallery pages.

### Icon Size

A minimum main icon size of 256x256 px is required to guarantee image quality.

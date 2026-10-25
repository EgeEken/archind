# Archive Indexation

A Windows app for sorting through and managing large photo and video archives.

The app runs locally. Indexing and ordinary browsing do not require an account or uploading your media or any sort of data collection.

**[Download the latest GitHub Release](https://github.com/EgeEken/archind/releases)** · [Report a problem or suggest a feature](https://github.com/EgeEken/archind/issues)

## What you can do

- **Browse an archive.** Index folders, inspect photo and video details, filter and search tools for convenience.

- **Search assets.** Search by filename or, after installing an optional model, describe what you're looking for in ordinary language (for example, "two kittens playing"). You can also find images visually similar to one you're viewing.

- **Get an automatic recommendation list of the best assets in your archive.** Near-identical photos are grouped together, ranked by an image-quality model and reviewed one by one to give you the model's recommended image among them.

- **Explore the collection.** There are timeline, geo map and visual similarity vector map views alongside the normal gallery.

- **Manage your archive** Inspect RAW/JPEG pairs and other representations, compare versions, and plan Copy, Move, Delete or compression operations by setting up custom rulesets. Supported workflows include JPEG XL, AVIF and AV1, depending on the source media. Changes are reviewed before they run so you get an estimate of how exactly this will effect your archive and file system.


## Getting started

1. Download the Windows installer from **[Releases](https://github.com/EgeEken/archind/releases)**. It is currently unsigned, so Windows may show a publisher or reputation warning.
2. Run the installer as your normal Windows user and open Archive Indexation.
3. Choose a folder containing photos or videos. The app creates a workspace index inside that folder; it doesn't move your media into a new library.
4. Let the initial scan finish, then open **Gallery** or **Groupings**. Use the filters and Select/Reject controls as you review your files.
5. If you want quality scoring or semantic search, use **Configure** to install the required models and run the corresponding analysis. Models may be large downloads and are not needed for basic browsing.
6. To update an existing workspace after adding or removing files, use **Re-index**.

The File Management tools can change or remove files when you explicitly approve an operation. Recommended to test them out on copied media first to figure out how it works before accidentally deleting something important permanently.

## Uninstalling

Use **Uninstall** on the app's Home screen or Windows **Installed apps**. Uninstalling removes the program and its managed AI runtimes and models; your managed archives, workspace indexes and saved settings remain.

## Planned roadmap for new features

- Faster gallery loading, more reliable re-indexing and clearer progress during long jobs and uninstall.
- Broader similarity groups, plus searching and ranking across multiple workspaces.
- Better image-quality assessment.
- More comprehensive RAW editing, including feathered local exposure masks and improved noise reduction.
- Facial recognition and people grouping, OCR and searchable video speech transcripts.

## Feedback

Please use [GitHub Issues](https://github.com/EgeEken/archind/issues) for bug reports and feature suggestions. For a bug, include your Windows version, what you were doing, what happened and how to reproduce it.

# Archive Indexation

A Windows app for sorting through large photo and video archives without having to reorganize everything first.

Point it at a folder and it builds a searchable index of the files already there. You can browse by date or folder, find similar images, compare shots from the same burst, and keep track of which ones you've selected. It also has tools for making smaller copies of photos and videos while keeping a record of their originals.

The app runs locally. Indexing and ordinary browsing do not require an account or uploading your media.

**Windows beta · 64-bit · Free to test**

**[Download from GitHub Releases](https://github.com/EgeEken/archind/releases)** · [Report a problem or suggest a feature](https://github.com/EgeEken/archind/issues)

The first public 1.0 beta is being prepared. The download will appear under Releases once the installer has been checked on a separate Windows machine. Look for **ArchiveIndexationBeta.exe**.

## What you can do

- **Browse an archive.** Index folders recursively, generate thumbnails, inspect photo and video details, and filter by folder, date, file type or review status. Files that have gone offline remain in the catalog.
- **Find things.** Search by filename or, after installing an optional model, describe what you're looking for in ordinary language. You can also find images visually similar to one you're viewing.
- **Sort through similar shots.** Near-identical photos can be grouped together, ranked by an image-quality model and reviewed one by one. Automatic recommendations are suggestions; your Select and Reject decisions are kept separately.
- **Explore the collection.** There are timeline, map and visual-similarity views alongside the normal gallery.
- **Manage copies and compressed versions.** Inspect RAW/JPEG pairs and other representations, compare versions, and plan Copy, Move, Delete or compression operations. Supported workflows include JPEG XL, AVIF and AV1, depending on the source media. Changes are reviewed before they run.

Image-quality scores are imperfect. A technically good photograph isn't necessarily your favorite, and the automatic choices aren't meant to replace your judgment.

## Getting started

1. Download the Windows installer from **[Releases](https://github.com/EgeEken/archind/releases)**. It is currently unsigned, so Windows may show a publisher or reputation warning. Check that the file came from this repository and compare its SHA-256 checksum with the one in the release notes.
2. Run the installer as your normal Windows user and open Archive Indexation.
3. Choose a folder containing photos or videos. The app creates a workspace index inside that folder; it doesn't move your media into a new library.
4. Let the initial scan finish, then open **Gallery** or **Groupings**. Use the filters and Select/Reject controls as you review your files.
5. If you want quality scoring or semantic search, use **Configure** to install the required models and run the corresponding analysis. Models may be large downloads and are not needed for basic browsing.

To update an existing workspace after adding or removing files, use **Re-index**.

The File Management tools can change or remove files when you explicitly approve an operation. Try them on copied media first, and keep backups of anything important.

## Uninstalling

Use **Uninstall** on the app's Home screen or Windows **Installed apps**. Uninstalling removes the program and its managed AI runtimes and models; your original media, workspace indexes and saved settings are intended to remain.

The beta does not have automatic updates yet. Check the [Releases page](https://github.com/EgeEken/archind/releases) for new builds.

## What's next

Work planned after the first Windows testing round includes:

- Faster gallery loading, more reliable re-indexing and clearer progress during long jobs and uninstall.
- A better photo review workspace: side-by-side comparisons, keyboard controls and undo.
- Broader similarity groups, plus searching and ranking across multiple workspaces.
- Better image-quality assessment, with more attention to the best shot *within* a group.
- Non-destructive RAW editing, including feathered local exposure masks and improved noise reduction.
- Later additions such as people grouping, OCR and searchable video transcripts.

The order may change based on bugs and feedback from testers.

## Feedback and licensing

Please use [GitHub Issues](https://github.com/EgeEken/archind/issues) for bug reports and feature suggestions. For a bug, include your Windows version, what you were doing, what happened and how to reproduce it. Logs can help, but check them for personal file paths before sharing. **Don't upload private photos or videos to report a bug.**

This public repository hosts releases and documentation. The application's development source is maintained separately. See [LICENSE.md](LICENSE.md) for the beta software terms; bundled third-party components have their own licenses and notices.

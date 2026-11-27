# Changelog

All notable Aether releases are documented here. The public release repository receives a copy of this file without the closed-source application code.

## [0.1.4] - 2026-11-27

Aether 0.1.4 makes it easier to return to your work and organize content across a vault.

- **Vault homepage.** Aether resumes your last open page or database. Choose a fallback in Settings. New installs open with a Main Vault and a Getting started page.
- **Drag and drop.** Drop content onto pages, databases, folders, and Trash. Reordering a sorted database can switch to custom order while preserving the rest of the order.
- **Trash.** Search in list or gallery view, restore or delete a selection, and get a warning when references block deletion.
- **Text snippets.** Converting a snippet to a page uses its first line as the title and keeps the rest in the document.
- **Interface.** Updated breadcrumbs, menus, and selection controls, with sidebar unpinning and direct close controls on audio and video previews. Keyboard reordering keeps items clear of Trash.

## [0.1.3] - 2026-11-25

A larger update with new ways to capture quick notes, organize your vault, and connect your ideas.

### Added

- **Flows:** Arrange pages and text snippets in a visual tree. Add existing content, drag nodes to reorganize branches, collapse sections, and focus on a subtree. Customize the layout with groups and labels.
- **Text snippets:** Capture small notes in a compact editor with Markdown formatting, tags, and a choice of destination. Preview snippets without leaving your current view, or open them in a dedicated view. Convert a snippet into a page when you need more room.
- **Folders:** Organize pages and databases without duplicating their content. Drag items into folders from the sidebar and other views.
- **Kanban databases:** Organize database items into columns, alongside gallery and table layouts.
- **Audio and video assets:** Store recordings and videos in your vault, add them to databases, and play them in the app using native playback with seeking. Video thumbnails are generated locally with WebKit. Audio waveforms use cached summaries generated with bounded memory, also shown as audio thumbnails.
- **PDF support:** Upload PDFs, drop or paste them into databases, and read them in the app. First-page thumbnails make documents easier to recognize.
- **Add link previews:** Paste a URL to preview its title, image, and description before adding it to your vault or a database.
- **Multiple-file uploads:** Add supported images, PDFs, audio, and video with drag and drop and individual progress indicators.
- **Connections:** Link pages, blocks, databases, images, and web links. Connections appear from either end and follow the content as it changes.
- **Dark mode:** Follow your system appearance or choose light or dark mode in Settings.
- Content tabs for navigating open items.
- Page cover images and custom database item previews.
- Bulk editing tools and vault-wide tag renaming, merging, and removal.

### Improved

- **Database editing:** Edit properties directly in cards and tables, create select options from cells, reorder columns, resize widths, and customize wrapping and visibility.
- **Property conversion:** Change property types while carrying over compatible values. Conversion uses best effort; values that cannot fit the new type become unassigned.
- **Drag and drop:** Reorder database items, tabs, sidebar pins, and configuration lists more consistently. Pin content by dragging titles, tabs, or nested page icons to the sidebar.
- **Sidebar menus:** Right-click a pinned item to rename it, inspect it, or unpin it, including when the sidebar is collapsed. Inspecting an item no longer requires opening it.
- **All items:** Standalone links, images, PDFs, audio, video, and text snippets appear alongside pages and databases. Separate Flow and Text snippet filters make content easier to find; folders stay in navigation.
- Improved image, PDF, video, and audio viewing, plus clearer document thumbnails aligned to the top of cards.
- Generated thumbnails follow light and dark mode, with improved cache invalidation when content or appearance changes.
- Improved block selection, drag-handle menus, folder navigation, and document editing.
- More consistent menus, dropdowns, form controls, notifications, and keyboard navigation across light and dark mode.

## [0.1.2] - 2026-08-26

### Added

- Added shared sidebar pins for pages and databases, including drag-and-drop reordering.
- Added fullscreen-aware title alignment for macOS windows.

### Changed

- Upgraded the backend to SeaORM 2.0.
- Improved vault card sizing on wide screens.
- Simplified sub-page block presentation and allowed the canvas frame to extend to the bottom edge.

### Fixed

- Preserved in-progress trailing spaces while editing page titles.

## [0.1.1] - 2026-08-19

### Added

- Added Terms of Service.

## [0.1.0] - 2026-08-18

### Added

- Initial Aether release documentation and macOS distribution workflow.

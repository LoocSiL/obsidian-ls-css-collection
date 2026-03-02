# LS File Explorer - File Type Colors

## Table of Contents
- [Description](#description)
- [Key Features](#key-features)
- [Installation](#installation)
- [Appearance Settings](#appearance-settings)
    - [1. General Settings](#1-general-settings)
    - [2. Obsidian Files](#2-obsidian-files)
    - [3. Attachments](#3-attachments)
    - [4. External Files](#4-external-files)
- [Usage Examples](#usage-examples)
- [Compatibility](#compatibility)
- [Acknowledgments](#acknowledgments)

---

## Description

This CSS snippet is designed to change the **text color of file names** in the Obsidian File Explorer based on their type (extension). It helps visually distinguish between notes, attachments, and other files, speeding up navigation through your vault.

The snippet integrates with the Style Settings plugin, providing a convenient interface for customizing colors and enabling/disabling colorization for each file category.

## Key Features

- **File Categorization:** All files are divided into logical groups for easy configuration.
- **Text Colorization:** Changes the color of the file name, leaving icons and background unchanged (for compatibility with other snippets).
- **Flexible Toggle:** You can independently enable or disable colorization for each category (Markdown, PDF, images, code, etc.).
- **Color Customization:** A custom color can be set for each category via the Style Settings interface.
- **Active File Control:** An option to either keep the file's type color when it is open (active) or revert it to the theme's standard active color.
- **Wide Extension Support:** The snippet covers most popular file types used within and outside of Obsidian.

## Installation

1.  Save the snippet file (`LS_File Explorer - File Type Colors.css`) into your Obsidian vault's `.obsidian/snippets/` folder.
2.  In Obsidian, open **Settings**.
3.  Go to the **Appearance** section.
4.  Scroll down to the **CSS snippets** block.
5.  Click the **Reload** button to see the list of available snippets.
6.  Enable the `LS File Explorer - File Type Colors` snippet using its toggle switch.

**Important:** To access the color settings, make sure you have the **Style Settings** plugin installed and enabled. After enabling the snippet, a new block `💢 LS CSS File Explorer - File Type Colors` will appear in the Style Settings.

## Appearance Settings

All settings are adjusted through the **Style Settings** plugin. Find the corresponding block in its settings list.

![Settings](../images/FileTypeColors_00.png)

### 1. General Settings

- **Apply color to active file:**
    - **Enabled:** If a file is open in the active tab, its name color in the explorer will match its file type (according to the settings below).
    - **Disabled (default):** The active file will be displayed with the standard color your theme uses for active items (usually a brighter or more contrasting color). File type colors are ignored in this case.

![General Settings](../images/FileTypeColors_01.png)

### 2. Obsidian Files

This section configures the main file types used directly within Obsidian.

- **Markdown:** Core notes (`.md` extension). Excludes Excalidraw files, which have the double extension `.excalidraw.md`.
- **Canvas:** Files for working with Canvas (`.canvas`).
- **Excalidraw:** Drawings and diagrams created with the Excalidraw plugin (`.excalidraw` and `.excalidraw.md`).
- **Base:** Files with the `.base` extension (used by some plugins).

For each of these categories, there is an **Enable** toggle and a **Color** picker field.

![Obsidian Files](../images/FileTypeColors_02.png)

### 3. Attachments

This section covers media files and documents often stored in an Obsidian vault.

- **PDF:** Documents in PDF format (`.pdf`).
- **Images:** Raster and vector images (`.png`, `.jpg`, `.gif`, `.svg`, `.webp`, etc.).
- **Video:** Video files (`.mp4`, `.mkv`, `.mov`, `.webm`, etc.).
- **Audio:** Audio files (`.mp3`, `.wav`, `.flac`, `.ogg`, etc.).

For each category, there is an **Enable** toggle and a **Color** picker field.

![Attachments](../images/FileTypeColors_03.png)

### 4. External Files

Files that are not native to Obsidian but can be added to the vault.

- **MS Office:** Microsoft Office documents (`.docx`, `.xlsx`, `.pptx`, as well as `.csv`, `.rtf`, and legacy formats `.doc`, `.xls`, `.ppt`).
- **Code:** Source code and data files (`.py`, `.js`, `.css`, `.html`, `.json`, `.yaml`, `.xml`, `.sh`, `.sql`, and others).
- **Other/Misc:** A category for all remaining file types not included in the previous groups. The color from this category is applied to them if it is enabled.

For each category, there is an **Enable** toggle and a **Color** picker field.

![External Files](../images/FileTypeColors_04.png)

## Usage Examples

- **Visual Typing:** Make all Markdown files blue and Canvas files pink to quickly find the desired content type.
- **Highlight Attachments:** Set bright colors for images and PDFs (e.g., yellow and red) so they stand out immediately in a list of notes.
- **Project Differentiation:** If you use Obsidian for programming notes, you can highlight code files with a distinct, muted color.
- **Combined Use with Background Pills:** This snippet works great alongside the "LS File Explorer - Background Pills" snippet, coloring the text inside the colored pills for a more informative interface.

## Compatibility

This snippet only changes text color and does not affect the explorer's structure. It should be compatible with most other snippets and themes, including "LS File Explorer - Background Pills". In case of conflicts, ensure this snippet loads after others so its rules take priority (the order in the snippets list can be changed by dragging).

## Acknowledgments

Thank you for using this snippet. If you have suggestions for improvement or have found a bug, please report it in the Telegram chat.

**Support Chat:** [excel_cad_bim_chat](https://t.me/excel_cad_bim_chat)
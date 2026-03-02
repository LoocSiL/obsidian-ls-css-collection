# LS File Explorer - Background Pills

## Table of Contents
- [Description](#description)
- [Key Features](#key-features)
- [Installation](#installation)
- [Appearance Settings](#appearance-settings)
    - [1. Display Modes](#1-mode-selection)
    - [2. Folders](#2-folders)
    - [3. Files](#3-files)
    - [4. Geometry](#4-geometry)
- [Usage Examples](#usage-examples)
- [Compatibility](#compatibility)
- [Acknowledgments](#acknowledgments)

---

## Description

This CSS snippet is designed to modify the appearance of the **File Explorer** in Obsidian. It adds colored background pills for files and folders, making navigation through your vault more visual and structured.

The snippet offers flexible settings via the `Settings > Appearance > CSS snippets` menu, allowing you to customize the explorer to match your theme and personal preferences.

## Key Features

- **Color Pills:** Files and folders are highlighted with separate, customizable colors.
- **Two Width Modes:**
    - **Full row:** The pill spans the entire width of the explorer.
    - **Inline:** The pill wraps only around the file or folder name (like a "pill").
- **Flexible Color Customization:** Separate colors for normal state, hover, active, and selected items. Colors are configured separately for files and folders.
- **Expanded Folder Highlighting:** An option to use a distinct color for folders that are currently expanded.
- **Icons:** Ability to replace the default folder arrows with icons, as well as add various icons for files based on their type (Markdown, Canvas, images, video, audio, etc.).
- **Geometry Control:** Adjust corner rounding, internal padding, and vertical spacing between items.
- **Wrapping for Long Names:** Enabling this option removes horizontal scroll and wraps overly long file and folder names to a new line.

## Installation

1.  Save the snippet file (`LS_File Explorer - Background Pills.css`) into your Obsidian vault's `.obsidian/snippets/` folder.
2.  In Obsidian, open **Settings**.
3.  Go to the **Appearance** section.
4.  Scroll down to the **CSS snippets** block.
5.  Click the **Reload** button to see the list of available snippets.
6.  Enable the `LS File Explorer - Background Pills` snippet using its toggle switch.

**Important:** To access the color settings, make sure you have the **Style Settings** plugin installed and enabled. After enabling the snippet, a new block `💢 LS CSS File Explorer - Background Pills` will appear in the Style Settings.

## Appearance Settings

All settings are adjusted through the standard Obsidian interface. After enabling the snippet, find the corresponding block at the bottom of the "Appearance" settings page.

![StyleSettings](/images/BackgroundPills_00.png)

### 1. Mode Selection

- **Pill width mode:** Choose one of two options.
    - *Full row:* The background pill stretches across the entire available width of the explorer.
    - *Inline:* The background pill wraps only around the name text.
- **Start background from text (for "Full row" mode):** If enabled, the background pill starts immediately after the icon/arrow, not covering the leftmost part of the row. If disabled, the pill spans the entire row.
- **Wrap long names:** Enable this option so that names which don't fit horizontally wrap to the next line. This removes horizontal scrolling.

![Mode Selection](/images/BackgroundPills_01.png)

### 2. Folders

- **Enable background for folders:** Master switch to apply settings to folders.
- **Show folder icons:** Replaces the default expansion arrows with closed and open folder icons.
- **Highlight expanded folders:** When enabled, expanded folders will use the color from the "Folder - active" field.

#### Folder Colors
- **Folder - default:** Background color for a closed folder in its normal state.
- **Folder - hover:** Background color when hovering the cursor over a folder.
- **Folder - active (expanded):** Background color for a folder that is expanded (showing its contents). Used if "Highlight expanded folders" is enabled.
- **Folder - selected:** Background color for a folder that is selected (e.g., when clicked on).

![Folders](/images/BackgroundPills_02.png)

### 3. Files

- **Enable background for files:** Master switch to apply settings to files.
- **Show file icons:** Adds an icon to the left of the file name, corresponding to its type. Supported types: Markdown (.md), Canvas (.canvas), Excalidraw (.excalidraw.md), images, audio, video, .webm, .loom.

#### File Colors
- **File - default:** Background color for a file in its normal state.
- **File - hover:** Background color when hovering the cursor over a file.
- **File - active:** Background color for the active file (e.g., the one open in the current tab).
- **File - selected:** Background color for a file that is selected (e.g., for renaming or moving).

![Files](/images/BackgroundPills_03.png)

### 4. Geometry

- **Pill border radius (px):** Determines the corner rounding radius for all pills.
- **Margin:**
    - *Vertical margin between rows:* Sets the vertical spacing between items (files and folders). Can be set to a negative value to make the list more compact.
- **Padding:**
    - *Horizontal padding (left/right):* Horizontal spacing from the text to the pill's edges.
    - *Vertical padding (top/bottom):* Vertical spacing from the text to the pill's edges.

![Geometry](/images/BackgroundPills_04.png)

## Usage Examples

- **Classic Look:** "Full row" mode, 6-8px rounding, small margins, muted colors.
- **Minimalism:** "Inline" mode, 12-16px rounding, contrasting colors for emphasis.
- **Improved Navigation:** Enable file and folder icons, configure bright colors for active and expanded items to navigate your note structure faster.

> [!TIP] 
> The pill background color can be made transparent—this allows for more interface customization possibilities!

## Compatibility

The snippet is developed for Obsidian and uses its standard CSS classes. It should work correctly with most themes, though minor conflicts may occur with third-party themes that also drastically change the explorer's style. For compatibility questions, you can ask in the author's chat.

## Acknowledgments

Thank you for using this snippet. If you have suggestions for improvement or have found a bug, please report it in the Telegram chat.

**Support Chat:** [excel_cad_bim_chat](https://t.me/excel_cad_bim_chat)
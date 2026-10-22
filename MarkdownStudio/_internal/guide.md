# Markdown Studio Guide

Markdown Studio is a Windows Markdown writer and reader with live preview.

## Opening and saving documents

- **File → New** creates a new document in a new tab.
- **File → Open** can open one or several `.md`, `.markdown`, or text files. Each document opens in its own tab.
- Click a tab to switch documents. Drag tabs to reorder them.
- Click a tab's close button, or press **Ctrl+W**, to close only that document.
- An asterisk (`*`) beside a tab name means that document has unsaved changes.
- Opening a file that is already open activates its existing tab instead of creating a duplicate.
- Double-clicking an associated `.md` file in Windows opens that file directly in Markdown Studio.
- If Markdown Studio is already running, double-clicking another `.md` file sends it to the running window and opens it in a new tab instead of starting another application window.
- **File → Save / Save As** writes the Markdown source as UTF-8.
- **File → Close** closes the active tab without exiting the application.
- **Search → Find...** (`Ctrl+F`) highlights every matching substring and provides Find Next and Find Previous.
- **Search → Replace...** (`Ctrl+H`) replaces the current match or all matches.
- Search is case-insensitive by default. Select **Case sensitive** when capitalization must match, or **Whole word (exact match)** to exclude matches inside longer words.
- **Export HTML** and **Export PDF** create readable output files.

## Display modes

| Mode | Shortcut | Description |
|---|---:|---|
| Split view | `Ctrl+1` | Equal-width editor and preview panels |
| Editor only | `Ctrl+2` | Markdown source fills the window |
| Preview only | `Ctrl+3` | Rendered document fills the window |
| Full screen | `F11` | Toggles full-screen mode |

The editor and preview scroll positions are synchronized while Split view is active.

Hold **Ctrl** and double-click text in the Preview window to jump to its Markdown source. If necessary, Markdown Studio changes to Split view, scrolls the Editor to the corresponding source location, places the cursor there, and activates the editing commands.

Web links clicked in the preview open in the Windows default browser, so the rendered Markdown document remains visible. In-document links such as `#display-modes` stay within the preview.

## Formatting toolbar

Select text, then use a toolbar button. Available commands include Bold, Italic, Strikethrough, text colour, background colour, ordered and bullet lists, task lists, tables, links, images, H1–H5, Paragraph, Code, Quote and Rule.

**Clear formatting** removes Markdown and HTML formatting markers from the selected text while preserving its readable content.

Toolbar and menu commands follow the active pane. Formatting, Find and Edit commands are active when the editor has focus and inactive when the preview has focus. Preview zoom commands are active when the preview has focus.

When **Preview only** is selected, switching tabs keeps every tab in Preview-only mode and keeps the Edit menu and Markdown formatting toolbar disabled.

## Code and syntax highlighting

Select multiple lines and click **Code**, then select a language such as `python`, `javascript`, `java`, `html`, `css`, `json`, `sql`, or `bash`. Syntax colours are produced locally by Pygments, so code highlighting works without an internet connection. The preview shows a light-grey code block with dark syntax-highlighted text.

## Advanced features

The preview supports tables, task lists, footnotes, definition lists, embedded HTML, Mermaid diagrams, MathJax equations and local images. Mermaid, MathJax and syntax-highlighting libraries require internet access.

## Keyboard shortcuts

| Command | Shortcut |
|---|---:|
| New | `Ctrl+N` |
| Open | `Ctrl+O` |
| Save | `Ctrl+S` |
| Save As | `Ctrl+Shift+S` |
| Close document | `Ctrl+W` |
| Find and highlight text | `Ctrl+F` |
| Jump from Preview to source | `Ctrl` + double-click |
| Bold | `Ctrl+B` |
| Italic | `Ctrl+I` |
| Insert link | `Ctrl+K` |
| Clear formatting | `Ctrl+Shift+R` |
| Open this guide | `F1` |

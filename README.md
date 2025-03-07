# PromptMD

PromptMD is a lightweight, browser-based prompt management tool that helps you create, organize, and edit text prompts with real-time Markdown preview. Built as a single HTML file with no external dependencies (except marked.js for Markdown rendering), it works entirely in your browser and stores all data locally.

<p align="center"><img src="screenshots/PromptMD-screenshot.png"></p>

## Downloads
You can <b>download</b> the latest release [HERE](https://github.com/DexterLagan/PromptMD/releases/).

## Version History

- v1.01
  - added automatic truncation of long prompt titles
  - editor switches to edit mode upon creating a new prompt
- v1.0 - initial release

## Features

### Core Functionality
- Create and edit prompts with automatic saving
- Real-time Markdown preview and editing
- Drag-and-drop prompt reordering
- Local storage for all your prompts
- Import/Export functionality for backup and sharing
- Responsive split-pane interface with adjustable width

### Rich Text Support
- Live Markdown preview
- Support for all common Markdown elements:
  - Headers
  - Lists (ordered and unordered)
  - Code blocks and inline code
  - Tables
  - Blockquotes
  - Links
  - Horizontal rules
- Built-in Markdown cheat sheet

### Organization
- Tag-based organization system
- Powerful search across titles, content, and tags
- Dynamic title generation from first line
- Clean, minimalist interface
- Smart content previews

### User Experience
- Keyboard shortcuts for common actions
- Auto-save with 500ms debounce
- Drag-and-drop reordering
- One-click copying to clipboard
- Quick access help modal
- Automatically truncate overly long prompt titles
- Automatically disables MD mode for new prompts

## Getting Started

1. Download the HTML file
2. Open it in your web browser
3. Start creating and managing your prompts!

No installation, no dependencies, no setup required.

## About Prompt Titles

PromptMD automatically labels each prompt using the first line of its content.
If the first line is long, it will truncate it.

## Keyboard Shortcuts

- `Ctrl + N`: Create new prompt
- `Ctrl + S`: Force save current prompt
- `Ctrl + F`: Focus search box
- `Ctrl + C`: Copy current prompt
- `Ctrl + M`: Toggle Markdown preview
- `Delete`: Delete selected prompt
- `?`: Show/hide help
- `Esc`: Close modal/Cancel edit

## Data Privacy

All data is stored locally in your browser using localStorage. No data is ever sent to any server.

## Browser Support

Works in all modern browsers that support:
- localStorage
- ES6+ JavaScript
- CSS Grid/Flexbox

## License

PromptMD is free software; see [LICENSE](https://github.com/DexterLagan/PromptMD/blob/main/LICENSE) for more details.

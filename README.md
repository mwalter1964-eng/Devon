# Devon

A Chrome/Edge browser extension that enhances Azure DevOps with rich text editing, dual-pane navigation, and work item previews.

## Features

- **Dual Pane Mode** - Split-panel navigation keeps the backlog visible while viewing work items
- **Work Item Preview** - Hover or click on work item links to see popup previews
- **TinyMCE Rich Text Editor** - Full-featured HTML editor for work item fields
- **Insert DevOps Link** - Quick linking to work items with live filtering
- **Table Editing** - Create and edit tables with captions, margins, and header styling
- **HTML Cleanup Tools** - Fix messy HTML from copy/paste operations

## Installation

### Chrome
1. Download/clone this repository
2. Open `chrome://extensions/`
3. Enable **Developer mode**
4. Click **Load unpacked**
5. Select the `browser-extension` folder

### Edge
1. Download/clone this repository
2. Open `edge://extensions/`
3. Enable **Developer mode**
4. Click **Load unpacked**
5. Select the `browser-extension` folder

## Configuration

1. Right-click the Devon icon in your browser toolbar
2. Click **Options**
3. Enter your Azure DevOps **Organization Name** and **Personal Access Token (PAT)**
4. Click **Save Options**

## Development

```bash
cd browser-extension
npm install
npm run build    # Build once
npm run watch    # Auto-rebuild on changes
```

## Distribution

To share with colleagues, zip the `browser-extension` folder. That's all they need.

## Documentation

- See `user_manual.md` for detailed usage instructions
- See `CLAUDE.md` for developer/AI assistant guidance

## License

This project is provided as-is for enhancing Azure DevOps workflows.

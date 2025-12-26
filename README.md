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

## Privacy Policy

  Last updated: December 2024

  Overview

  Devon is a browser extension that enhances Azure DevOps with dual-pane navigation, work item previews, and an improved rich text editor. This policy describes how the extension handles user data.

  Data Collection

  Devon collects and stores the following data locally in your browser:

  - Azure DevOps Personal Access Token (PAT): Used to authenticate API calls to read and update work items. Stored in Chrome sync storage.
  - User preferences: Settings such as dual-pane mode state and editor configuration.

  Data Usage

  All collected data is used solely to provide the extension's functionality:
  - Your PAT is sent only to Azure DevOps APIs (dev.azure.com, visualstudio.com) to authenticate requests.
  - Preferences are stored locally to maintain your settings across sessions.

  Data Sharing

  Devon does not:
  - Sell or transfer any user data to third parties
  - Collect analytics or telemetry
  - Track browsing history or user activity
  - Send data to any servers other than Azure DevOps

  Data Storage

  All data remains in your browser's local storage and Chrome sync storage. No data is transmitted to external servers controlled by the extension developer.

  Contact

  For questions about this privacy policy, contact your organization's IT administrator.

# vscode-settings

A repo for my VS Code settings.

# Settings

```json
{
  "editor.cursorBlinking": "phase",
  "editor.fontLigatures": true,
  "editor.fontWeight": "normal",
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.wordWrap": "on",
  "editor.guides.bracketPairsHorizontal": "active",
  "editor.fontSize": 14,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "window.menuBarVisibility": "compact",
  "window.zoomLevel": 0.25,
  "workbench.colorTheme": "Solidity Visual Developer Dark",
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 10,
  "security.workspace.trust.untrustedFiles": "open",
  "html.autoClosingTags": false,
  "markdown.preview.fontSize": 14,
  "markdown-preview-enhanced.previewTheme": "github-dark.css",
  "prettier.singleQuote": true,
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "jupyter.interactiveWindow.textEditor.executeSelection": true,
  "interactiveWindow.executeWithShiftEnter": true,

  // Language-specific settings
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "yzhang.markdown-all-in-one"
  },
  "[python]": {
    "editor.formatOnType": true,
    "editor.defaultFormatter": "charliermarsh.ruff"
  },

  // Solidity settings
  "solidity.formatter": "forge",
  "solidity.packageDefaultDependenciesContractsDirectory": "src",
  "solidity.packageDefaultDependenciesDirectory": "lib",
  "solidity.telemetry": false,

  // Accessibility
  "editor.accessibilitySupport": "off",

  // Editor decorations and control characters
  "explorer.decorations.badges": false,
  "editor.renderControlCharacters": false,

  // Additional settings for consistency and enhancements
  "workbench.sash.hoverDelay": 0,
  "workbench.sash.size": 1,
  "cSpell.dictionaryDefinitions": [],
  "editor.guides.bracketPairs": "active",
  "workbench.editor.labelFormat": "medium",
  "supermaven.enable": {
    "*": true
  },
  "cSpell.enableFiletypes": ["solidity"],
  "cSpell.userWords": ["Chainlink", "Diwald"]
}

```

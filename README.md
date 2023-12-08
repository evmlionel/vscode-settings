# vscode-settings

A repo for my VS Code settings.

# Settings

```json
{
  // Editor Settings
  "editor.bracketPairColorization.enabled": true,
  "editor.cursorBlinking": "phase",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.fontWeight": "normal",
  "editor.formatOnPaste": false,
  "editor.formatOnSave": true,
  "editor.lineHeight": 0,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.renderControlCharacters": false,
  "editor.renderWhitespace": "all",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.accessibilitySupport": "off",

  // Explorer Settings
  "explorer.decorations.badges": false,

  // HTML Settings
  "html.autoClosingTags": false,

  // Prettier Settings
  "prettier.singleQuote": true,

  // Security Settings
  "security.workspace.trust.untrustedFiles": "open",

  // Terminal Settings
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.fontSize": 14,
  "terminal.external.osxExec": "Warp.app",

  // Window Settings
  "window.menuBarVisibility": "compact",
  "window.zoomLevel": 0.2,

  // Workbench Settings
  "workbench.colorCustomizations": {},
  "workbench.iconTheme": "material-icon-theme",
  "workbench.sash.hoverDelay": 0,
  "workbench.sash.size": 1,
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 10,

  // Markdown Settings
  "markdown.preview.fontSize": 14,
  "markdown-preview-enhanced.previewTheme": "github-dark.css",

  // Custom Inline Bookmark Styles
  "inline-bookmarks.expert.custom.styles": {
    "blue": {
      "color": "#5C5CFF",
      "gutterIconColor": "#5C5CFF"
    },
    // Other color definitions...
  },
  "inline-bookmarks.expert.custom.words.mapping": {
    "blue": ["@audit[\\s]"],
    // Other mappings...
  },

  // Language-specific Settings
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.formatOnType": true
  },
  // "[solidity]": {
  //   "editor.defaultFormatter": "JuanBlanco.solidity"
  // },

  // Solidity Settings
  "solidity.formatter": "forge",
  "solidity.packageDefaultDependenciesContractsDirectory": "src",
  "solidity.packageDefaultDependenciesDirectory": "lib",
  "solidity.telemetry": false,

  // GitHub Copilot Settings
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },

  // Live Server Settings
  "liveServer.settings.donotShowInfoMsg": true,

  // Spell Checker Settings
  "cSpell.dictionaryDefinitions": []
}
```

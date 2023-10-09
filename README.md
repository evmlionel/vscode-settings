# vscode-settings

A repo for my VS Code settings.

# Settings

```json
{
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

  "explorer.decorations.badges": false,

  "html.autoClosingTags": false,

  "prettier.singleQuote": true,

  "security.workspace.trust.untrustedFiles": "open",

  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.fontSize": 14,

  "window.menuBarVisibility": "compact",
  "window.zoomLevel": 0.2,

  "workbench.colorCustomizations": {},
  "workbench.iconTheme": "material-icon-theme",
  "workbench.sash.hoverDelay": 0,
  "workbench.sash.size": 1,
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 10,

  "markdown.preview.fontSize": 14,
  "markdown-preview-enhanced.previewTheme": "github-dark.css",

  "cSpell.dictionaryDefinitions": [],

  "inline-bookmarks.expert.custom.styles": {
    "blue": {
      "color": "#5C5CFF",
      "gutterIconColor": "#5C5CFF"
    },
    "dark-green": {
      "color": "#00A300",
      "gutterIconColor": "#00A300"
    },
    "green": {
      "color": "#8AFF8A",
      "gutterIconColor": "#8AFF8A"
    },
    "purple": {
      "color": "#9932CC",
      "gutterIconColor": "#9932CC"
    },
    "red": {
      "color": "#BA0F30",
      "gutterIconColor": "#BA0F30"
    },
    "yellow": {
      "color": "#FFC300",
      "gutterIconColor": "#FFC300"
    }
  },

  "inline-bookmarks.expert.custom.words.mapping": {
    "blue": ["@audit[\\s]"],
    "dark-green": ["@audit\\-submitted[\\s]"],
    "green": ["@audit\\-ok[\\s]"],
    "purple": ["@audit\\-info[\\s]"],
    "red": ["@audit\\-issue[\\s]"],
    "yellow": ["@audit\\-check[\\s]"]
  },

  "terminal.external.osxExec": "Warp.app",

  "liveServer.settings.donotShowInfoMsg": true,

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

  "[solidity]": {
    "editor.defaultFormatter": "JuanBlanco.solidity"
  },

  "solidity.formatter": "forge",
  "solidity.packageDefaultDependenciesContractsDirectory": "src",
  "solidity.packageDefaultDependenciesDirectory": "lib",
  "solidity.telemetry": false
}
```

# vscode-settings

A repo for my VS Code settings.

# Settings

```json
{
  // Editor Core Settings
  "editor.fontSize": 14,
  "editor.fontWeight": "normal",
  "editor.fontLigatures": true,
  "editor.cursorBlinking": "phase",
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.wordWrap": "on",
  "editor.accessibilitySupport": "off",
  "editor.renderControlCharacters": false,
  "editor.suggestSelection": "first",
  "editor.guides.bracketPairs": "active",
  "editor.guides.bracketPairsHorizontal": "active",

  // Formatting & Code Style
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": ["source.fixAll.eslint"],
  "prettier.singleQuote": true,
  "prettier.semi": false,
  "prettier.trailingComma": "es5",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,

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
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "yzhang.markdown-all-in-one"
  },
  "[python]": {
    "editor.formatOnType": true,
    "editor.defaultFormatter": "charliermarsh.ruff"
  },

  // Workbench & UI
  "workbench.colorTheme": "Atom One Dark",
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 10,
  "workbench.editor.labelFormat": "medium",
  "workbench.activityBar.location": "top",
  "workbench.activityBar.orientation": "vertical",
  "workbench.sash.hoverDelay": 0,
  "workbench.sash.size": 1,
  "window.menuBarVisibility": "compact",
  "window.zoomLevel": 0.25,

  // Terminal
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultProfile.windows": "Git Bash",

  // File Associations & Imports
  "files.associations": {
    "*.tsx": "typescriptreact"
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",

  // Markdown & Documentation
  "markdown.preview.fontSize": 14,
  "markdown-preview-enhanced.previewTheme": "github-dark.css",

  // Security & Trust
  "security.workspace.trust.untrustedFiles": "open",

  // GitHub Copilot
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },

  // Solidity
  "solidity.formatter": "forge",
  "solidity.packageDefaultDependenciesContractsDirectory": "src",
  "solidity.packageDefaultDependenciesDirectory": "lib",
  "solidity.telemetry": false,

  // Live Server
  "liveServer.settings.donotShowInfoMsg": true,

  // Jupyter
  "jupyter.interactiveWindow.textEditor.executeSelection": true,
  "interactiveWindow.executeWithShiftEnter": true,

  // Cursor & SuperMaven
  "cursor.cpp.disabledLanguages": ["plaintext", "scminput"],
  "cursor.cmdk.useThemedDiffBackground": true,
  "supermaven.enable": {
    "*": true
  },

  // Spell Checker
  "cSpell.dictionaryDefinitions": [],
  "cSpell.enableFiletypes": ["solidity"],
  "cSpell.userWords": ["Chainlink", "Diwald"],

  // HTML
  "html.autoClosingTags": false,

  // Explorer
  "explorer.decorations.badges": false,
  "symbols.hidesExplorerArrows": false,

  // Highlight Rules
  "highlight.regexes": {
    "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *TODO(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
      "filterFileRegex": ".*(?<!CHANGELOG.md)$",
      "decorations": [
        {
          "overviewRulerColor": "#ffcc00",
          "backgroundColor": "#ffcc00",
          "color": "#1f1f1f",
          "fontWeight": "bold"
        },
        {
          "backgroundColor": "#ffcc00",
          "color": "#1f1f1f"
        }
      ]
    },
    "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *(?:FIXME|FIX|BUG|UGLY|DEBUG|HACK)(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
      "filterFileRegex": ".*(?<!CHANGELOG.md)$",
      "decorations": [
        {
          "overviewRulerColor": "#cc0000",
          "backgroundColor": "#cc0000",
          "color": "#1f1f1f",
          "fontWeight": "bold"
        },
        {
          "backgroundColor": "#cc0000",
          "color": "#1f1f1f"
        }
      ]
    },
    "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *(?:REVIEW|OPTIMIZE|TSC)(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
      "filterFileRegex": ".*(?<!CHANGELOG.md)$",
      "decorations": [
        {
          "overviewRulerColor": "#00ccff",
          "backgroundColor": "#00ccff",
          "color": "#1f1f1f",
          "fontWeight": "bold"
        },
        {
          "backgroundColor": "#00ccff",
          "color": "#1f1f1f"
        }
      ]
    },
    "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *(?:IDEA)(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
      "filterFileRegex": ".*(?<!CHANGELOG.md)$",
      "decorations": [
        {
          "overviewRulerColor": "#cc00cc",
          "backgroundColor": "#cc00cc",
          "color": "#1f1f1f",
          "fontWeight": "bold"
        },
        {
          "backgroundColor": "#cc00cc",
          "color": "#1f1f1f"
        }
      ]
    }
  }
}


```

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
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": ["source.fixAll.eslint"],
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "window.menuBarVisibility": "compact",
  "window.zoomLevel": 0.25,
  "workbench.colorTheme": "Default Dark Modern",
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 10,
  "workbench.editor.labelFormat": "medium",
  "security.workspace.trust.untrustedFiles": "open",
  "html.autoClosingTags": false,
  "markdown.preview.fontSize": 14,
  "markdown-preview-enhanced.previewTheme": "github-dark.css",
  "prettier.singleQuote": true,
  "prettier.semi": false,
  "prettier.trailingComma": "es5",
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "jupyter.interactiveWindow.textEditor.executeSelection": true,
  "interactiveWindow.executeWithShiftEnter": true,
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
  "solidity.formatter": "forge",
  "solidity.packageDefaultDependenciesContractsDirectory": "src",
  "solidity.packageDefaultDependenciesDirectory": "lib",
  "solidity.telemetry": false,
  "editor.accessibilitySupport": "off",
  "explorer.decorations.badges": false,
  "editor.renderControlCharacters": false,
  "workbench.sash.hoverDelay": 0,
  "workbench.sash.size": 1,
  "cSpell.dictionaryDefinitions": [],
  "editor.guides.bracketPairs": "active",
  "supermaven.enable": {
    "*": true
  },
  "cSpell.enableFiletypes": ["solidity"],
  "cSpell.userWords": ["Chainlink", "Diwald"],
  "cursor.cpp.disabledLanguages": ["plaintext", "scminput"],
  "files.associations": {
    "*.tsx": "typescriptreact"
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.suggestSelection": "first",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "editor.renderWhitespace": "all",
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
  },
  "cursor.cmdk.useThemedDiffBackground": true,
  "symbols.hidesExplorerArrows": false,
  "editor.fontSize": 14,
  "workbench.activityBar.location": "top",
  "workbench.activityBar.orientation": "vertical"
}

```

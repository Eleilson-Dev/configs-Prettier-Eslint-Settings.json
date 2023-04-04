# configs-Prettier-Eslint-Settings.json

# my configs prettier

{
  "semi": true,
  "arrowParens": "always",
  "editorconfig": true,
  "proseWrap": "always",
  "printWidth": 60,
  "singleQuote": true,
  "tabWidth": 2,
  "jsxSingleQuote": true,
  "trailingComma": "all",
  "bracketSpacing": true,
  "BracketLine": true
}

# my configs Eslint

{
  "env": {
    "browser": true,
    "es2021": true,
    "jest": true
  },
  "extends": ["eslint:recommended"],
  "overrides": [],
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module"
  },
  "rules": {
    "quotes": ["error", "single"],
    "arrow-body-style": ["error", "always"],
    "eqeqeq": ["error", "always"],
    "curly": ["error"],
    "no-multiple-empty-lines": ["error", { "max": 1 }],
    "no-empty-pattern": "error",
    "object-curly-spacing": ["error", "always"],
    "no-trailing-spaces": "error"
  }
}

# my configs settings.json

{
  // Workbench
  "workbench.colorTheme": "Dracula",
  "workbench.iconTheme": "material-icon-theme",
  "code-runner.clearPreviousOutput": true,
  "explorer.confirmDelete": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "explorer.confirmDragAndDrop": false,
  "git.openRepositoryInParentFolders": "always",
  "editor.minimap.renderCharacters": false,
  "editor.minimap.enabled": false,
  "editor.tabSize": 2,
  // editor action on save
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  // Explorer
  "explorer.compactFolders": false,
  // editor default formater
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "window.zoomLevel": 1,
  "workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#5caeef",
    "editorBracketHighlight.foreground2": "#dfb976",
    "editorBracketHighlight.foreground3": "#c172d9",
    "editorBracketHighlight.foreground4": "#4fb1bc",
    "editorBracketHighlight.foreground5": "#97c26c",
    "editorBracketHighlight.foreground6": "#abb2c0",
    "editorBracketHighlight.unexpectedBracket.foreground": "#db6165"
  }
}

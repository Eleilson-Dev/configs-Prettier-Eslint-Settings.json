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

# my configs Eslint-react-with-typescript 

{
  "env": {
    "browser": true,
    "es2021": true,
    "node": true,
    "jest": true
  },
  "extends": [
    "eslint:recommended",
    "plugin:react/recommended",
    "plugin:react-hooks/recommended",
    "plugin:@typescript-eslint/recommended"
  ],
  "settings": {
    "react": {
      "version": "detect"
    }
  },
  "overrides": [],
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaFeatures": { "jsx": true },
    "ecmaVersion": "latest",
    "sourceType": "module"
  },
  "plugins": ["react", "@typescript-eslint", "react-hooks", "react-refresh"],
  "rules": {
    "react-refresh/only-export-components": "warn",
    "quotes": ["error", "single"],
    "arrow-body-style": ["error", "always"],
    "eqeqeq": ["error", "always"],
    "curly": ["error"],
    "no-multiple-empty-lines": ["error", { "max": 1 }],
    "no-empty-pattern": "error",
    "object-curly-spacing": ["error", "always"],
    "no-trailing-spaces": "error",
    "react/react-in-jsx-scope": "off",
    "no-unused-vars": "warn"
  }
}

# my configs Eslint-react-js

{
  "env": {
    "browser": true,
    "es2021": true,
    "node": true,
    "jest": true
  },
  "extends": [
    "eslint:recommended",
    "plugin:react/recommended",
    "plugin:react-hooks/recommended"
  ],
  "overrides": [],
  "parserOptions": {
    "ecmaFeatures": { "jsx": true },
    "ecmaVersion": "latest",
    "sourceType": "module"
  },
  "settings": {
    "react": {
      "version": "detect"
    }
  },
  "plugins": ["react", "react-hooks"],
  "rules": {
    "quotes": ["error", "single"],
    "arrow-body-style": ["error", "always"],
    "eqeqeq": ["error", "always"],
    "curly": ["error"],
    "no-multiple-empty-lines": ["error", { "max": 1 }],
    "no-empty-pattern": "error",
    "object-curly-spacing": ["error", "always"],
    "no-trailing-spaces": "error",
    "react/react-in-jsx-scope": "off",
    "no-unused-vars": "warn"
  }
}

# my configs settings.json

{
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
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
    "source.fixAll.eslint": true,
    "source.fixAll": true
  },
  // Explorer
  "explorer.compactFolders": false,
  // editor default formater
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#c661f5",
    "editorBracketHighlight.foreground2": "#33b8f2",
    "editorBracketHighlight.foreground3": "#54e4a6",
    "editorBracketHighlight.foreground4": "#4fb1bc",
    "editorBracketHighlight.foreground5": "#97c26c",
    "editorBracketHighlight.foreground6": "#dfb976",
    "editorBracketHighlight.unexpectedBracket.foreground": "#db6165"
  },
  "editor.codeLensFontSize": 1,
  "window.zoomLevel": 1,
  "editor.fontWeight": "500"
}

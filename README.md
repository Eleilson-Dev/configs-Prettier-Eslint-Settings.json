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
    "plugin:react-hooks/recommended",
    "prettier"
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
  "plugins": ["react", "react-hooks", "prettier"],
  "rules": {
    "prettier/prettier": "error",
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

devDependencies for react eslint end prettier {
    "eslint": "^8.36.0",
    "eslint-config-prettier": "^9.1.0",
    "eslint-plugin-prettier": "^5.0.1",
    "eslint-plugin-react": "^7.32.2",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.5",
    "prettier": "^3.1.1"
}

# my configs settings.json

{
  "editor.fontFamily": "Cascadia code",
  "editor.fontLigatures": true,
  "workbench.iconTheme": "symbols",
  "code-runner.clearPreviousOutput": true,
  "explorer.confirmDelete": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "explorer.confirmDragAndDrop": false,
  "git.openRepositoryInParentFolders": "always",
  "editor.minimap.renderCharacters": false,
  "editor.tabSize": 2,
  // editor action on save
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.fixAll": "explicit"
  },
  // essa parte configura um file do eslint e prettir
  "editor.formatOnSave": true,
  "eslint.enable": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.singleQuote": true,
  // Explorer
  "explorer.compactFolders": false,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
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
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.wordWrap": "on",
  "editor.fontSize": 14,
  "gitlens.currentLine.enabled": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "window.zoomLevel": 1,
  //desativando a menuTopBar
  "window.menuBarVisibility": "hidden",
  "workbench.colorTheme": "Dracula",
  "symbols.hidesExplorerArrows": false,
  "workbench.startupEditor": "newUntitledFile",
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "editor.minimap.enabled": false,
  "workbench.activityBar.location": "hidden",
  "workbench.statusBar.visible": false,
  "breadcrumbs.enabled": false
}

=============================================================================================================================

# passo a passo pra usar o eslint o prittier com typescript puro

primeiro passo => {  install npm install --save-dev @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint typescript  }

# segundo passo installar o prettier/eslint com as config => {
	npm install prettier --save-dev
	npm install eslint-plugin-prettier --save-dev
	npm install eslint-config-prettier --save-dev
}

# config eslint para typescript com prettier em js //

module.exports = {
  env: {
    browser: true,
    es6: true,
    node: true,
  },
  extends: [
    'eslint:recommended',
    'plugin:@typescript-eslint/eslint-recommended',
    'plugin:@typescript-eslint/recommended',
    'plugin:prettier/recommended',
  ],
  globals: {
    Atomics: 'readonly',
    SharedArrayBuffer: 'readonly',
  },
  parser: '@typescript-eslint/parser',
  parserOptions: {
    ecmaVersion: 11,
    sourceType: 'module',
  },
  plugins: ['@typescript-eslint'],
  rules: {},
};


# prettier config em js // 

module.exports = {
  semi: true,
  trailingComma: 'all',
  singleQuote: true,
  printWidth: 80,
  tabWidth: 2,
};



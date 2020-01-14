User Settings:

```
{
  // Theme Setup.
  "workbench.colorTheme": "Noctis Uva",
  "workbench.iconTheme": "vscode-icons",
  "terminal.integrated.fontFamily": "Hack",
  "editor.fontSize": 12,
  "editor.fontFamily": "Hack",
  "editor.lineHeight": 19,
  "editor.letterSpacing": 0.5,
  "editor.fontWeight": "bold",
  "editor.fontLigatures": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  "editor.renderWhitespace": "all",
  "editor.snippetSuggestions": "top",
  "editor.formatOnSave": true,
  "workbench.startupEditor": "newUntitledFile",
  "editor.glyphMargin": true,
  "workbench.editor.enablePreview": false,
  "explorer.confirmDragAndDrop": false,
  "files.trimTrailingWhitespace": true,
  "files.trimFinalNewlines": true,
  // MacOS Only Settings.
  "workbench.fontAliasing": "auto",
  "terminal.integrated.macOptionIsMeta": true,
  // SOP's Import Cost Extension Settings.
  "importCost.largePackageColor": "#EC3A37F5",
  "importCost.mediumPackageColor": "#B362FF",
  "importCost.smallPackageColor": "#B362FF",
  "git.confirmSync": false,
  "terminal.integrated.fontSize": 11,
  "explorer.openEditors.visible": 12,
  "extensions.ignoreRecommendations": true,
  "explorer.confirmDelete": false,
  "git.autofetch": true,
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/.next": true
  },
  // turn it off for JS
  "[javascript]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.autoFixOnSave": true,
  "prettier.disableLanguages": [
    "js",
    "javascriptreact"
  ],
  "eslint.alwaysShowStatus": true,
  "cSpell.userWords": [
    "Unmount",
    "esversion",
    "fullpage",
    "fussion",
    "keycloak",
    "middlewares",
    "todos"
  ],
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "vsicons.dontShowNewVersionMessage": true,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": false,
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "colorize.languages": [
    "javascript"
  ],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "window.zoomLevel": -0.3
}
```



-----------------	*************	-----------------




Key Bindings:

```
// Place your key bindings in this file to overwrite the defaults
[
  {
    "key": "cmd+alt+t",
    "command": "workbench.action.terminal.new"
  },
  {
    "key": "shift+cmd+l",
    "command": "editor.action.formatSelection",
    "when": "editorHasDocumentSelectionFormattingProvider && editorHasSelection && editorTextFocus && !editorReadonly"
  },
  {
    "key": "alt+cmd+l",
    "command": "editor.action.formatSelection",
    "when": "editorHasDocumentSelectionFormattingProvider && editorHasSelection && editorTextFocus && !editorReadonly"
  },
  {
    "key": "shift+cmd+l",
    "command": "beautify.format"
  },
  {
    "key": "ctrl+alt+up",
    "command": "editor.action.insertCursorAbove",
    "when": "editorTextFocus"
  },
  {
    "key": "alt+cmd+up",
    "command": "-editor.action.insertCursorAbove",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+alt+down",
    "command": "editor.action.insertCursorBelow",
    "when": "editorTextFocus"
  },
  {
    "key": "alt+cmd+down",
    "command": "-editor.action.insertCursorBelow",
    "when": "editorTextFocus"
  }
]
```



-----------------	*************	-----------------




Extensions:

```
code --install-extension ahmadawais.shades-of-purple
code --install-extension christian-kohler.path-intellisense
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension dbaeumer.vscode-eslint
code --install-extension dcortes92.FreeMarker
code --install-extension donjayamanne.githistory
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension dunstontc.viml
code --install-extension eamodio.gitlens
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension fknop.vscode-npm
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension formulahendry.code-runner
code --install-extension formulahendry.terminal
code --install-extension jasonnutter.search-node-modules
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension kamikillerto.vscode-colorize
code --install-extension kumar-harsh.graphql-for-vscode
code --install-extension leveluptutorials.theme-levelup
code --install-extension liviuschera.noctis
code --install-extension michelemelluso.code-beautifier
code --install-extension mohsen1.prettify-json
code --install-extension mrmlnc.vscode-scss
code --install-extension qinjia.view-in-browser
code --install-extension Rubymaniac.vscode-paste-and-indent
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension vscode-icons-team.vscode-icons
code --install-extension wix.vscode-import-cost
code --install-extension wwm.better-align
code --install-extension xabikos.ReactSnippets
```



-----------------	*************	-----------------




Snippets

**css.json**

```
{
  "ThemeProps": {
    "prefix": ":tp",
    "body": ["${props => props.theme.$1};", "$2"],
    "description": "Use React styled-component"
  }
}
```

**javacsript.json**

```
{
  "Print to console": {
    "prefix": "clog",
    "body": ["console.log('$1');", "$2"],
    "description": "Log output to console"
  }
}
```

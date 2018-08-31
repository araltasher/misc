User Settings:

```
{
    "editor.fontFamily": "Hack, Menlo, monospace",
    "editor.fontSize": 11,
    "editor.letterSpacing": 0.3,
    "editor.lineHeight": 16.2,
    "window.zoomLevel": -0.3,
    "vsicons.dontShowNewVersionMessage": true,
    "workbench.iconTheme": "vscode-icons",
    "git.confirmSync": false,
    "terminal.integrated.fontSize": 11,
    "explorer.openEditors.visible": 0,
    "extensions.ignoreRecommendations": true,
    "explorer.confirmDelete": false,
    "workbench.startupEditor": "newUntitledFile",
    "workbench.colorTheme": "Level Up",
    "vsicons.projectDetection.autoReload": true,
    "git.autofetch": true,
    "terminal.integrated.fontFamily": "Hack",
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
    "key": "shift+alt+f",
    "command": "editor.action.formatDocument",
    "when": "editorTextFocus && !editorReadonly"
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
  }
]
```



-----------------	*************	-----------------




Extensions:

```
code --install-extension christian-kohler.path-intellisense
code --install-extension dbaeumer.jshint
code --install-extension dbaeumer.vscode-eslint
code --install-extension dracula-theme.theme-dracula
code --install-extension dustinsanders.an-old-hope-theme-vscode
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension JuanBlanco.solidity
code --install-extension leveluptutorials.theme-levelup
code --install-extension mohsen1.prettify-json
code --install-extension mrmlnc.vscode-scss
code --install-extension naumovs.theme-oceanicnext
code --install-extension robertohuertasm.vscode-icons
code --install-extension robinbentley.sass-indented
code --install-extension Rubymaniac.vscode-paste-and-indent
code --install-extension xabikos.ReactSnippets
```

# Origamid Next - Visual Studo Code Setup

![Screenshot](https://github.com/origamid/origamid-next-vscode/raw/master/./screenshot.png?raw=true)

# Instalação

1. Abrir o **Extensions** sidebar panel no VS Code. `View → Extensions`
2. Procurar por `Origamid Theme`
3. Clicar em **Install**
4. Clicar em **Reload**
5. Ir em Code > Preferences > Color Theme > **Origamid Next**

## Tipografia Recomendada

[IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)

Essa é a mesma tipografia que utilizo no site da Origamid. As itálicas são lindas e por isso não canso de usar a mesma.

## Configurações Recomendadas

Extensões

```
$ code --install-extension

origamid.origamid-next
dbaeumer.vscode-eslint
esbenp.prettier-vscode
naumovs.color-highlight
ritwickdey.LiveServer
octref.vetur
dsznajder.es7-react-js-snippets
claudiosanches.woocommerce
wordpresstoolbox.wordpress-toolbox
```

```js
{
  "editor.fontFamily": "IBM Plex Mono, Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.lineHeight": 25,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "window.zoomLevel": 0,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.activityBar.visible": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "explorer.confirmDragAndDrop": false,
  "diffEditor.renderSideBySide": true,
  "editor.formatOnSave": true,
  "html.autoClosingTags": false,
  "editor.autoIndent": false,
  "editor.colorDecorators": false,
  "editor.autoClosingBrackets": "always",
  "editor.autoClosingQuotes": "always",
  "files.associations": {
    "*.js": "javascriptreact"
  },
  "workbench.colorTheme": "Origamid",
  "workbench.iconTheme": "origamid-icons",
  "editor.minimap.renderCharacters": false,
  "breadcrumbs.enabled": false,
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "color-highlight.markerType": "dot-before",
  "editor.renderWhitespace": "selection",
  "workbench.statusBar.visible": true,
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "explorer.sortOrder": "type",
  "window.title": "${activeEditorMedium}${separator}${rootName}",
}
```

# MyFav VS CODE configurations

This is a collection of various VS Code extensions, themes and fonts, settings for a smooth development environment

## Extensions

1. `Auto Close Tag` - Simplified HTML/JSX/XML Markup
2. `Auto Rename Tag` - Easy to rename an Existing HTML/JSX/XML
3. `Babel ES6/ES7` - Supports ECMAScript 2015, 2016 versions and color markups
4. `Blockman` - (Optional) Highlights the block scope of the Code
5. `Cobalt2 Theme official` - The go to theme
6. `Color highlight` - Highlights the CSS3 hash code colors
7. `ES7+ React/Redux/React-Native snippets` - Ready Snippets for React and Reduxfig
8. `ESLint` - A tool to check the latest lintings
9. `Gitlens` - Generally to track the line by line code author
10. `Prettier` - Code Formatter Tool
11. `Thunder Client` - REST API caller for vs code. Eliminates the need for POSTMAN
12. `Glean` - Component formatter for React
13. `Material UI Icon` - The theme for material ui icons

## Fonts

1. [Cascadia Code](https://github.com/microsoft/cascadia-code) by Microsoft

## vscode configs

```
{
  "workbench.colorTheme": "Cobalt2",
  "editor.fontFamily": "'cascadia code', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "window.title": "${activeEditorShort}${separator}${rootName}",
  "workbench.iconTheme": "material-icon-theme",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "files.autoSave": "onFocusChange",
  "editor.tabSize": 2,
  "blockman.n01LineHeight": 0,
  "workbench.colorCustomizations": {
    "editor.lineHighlightBackground": "#1073cf2d",
    "editor.lineHighlightBorder": "#9fced11f"
  },
  "editor.wordWrap": "off",
  "diffEditor.wordWrap": "off",
  "editor.guides.indentation": false,
  "editor.guides.bracketPairs": false,
  "editor.inlayHints.enabled": false,
  "window.zoomLevel": 1,
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "auto-close-tag.excludedTags": [

    "area",
    "base",
    "br",
    "col",
    "command",
    "embed",
    "hr",
    "img",
    "input",
    "keygen",
    "link",
    "meta",
    "param",
    "source",
    "track",
    "wbr"
  ]
}
```

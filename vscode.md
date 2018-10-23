# User Settings

```js
{
  "window.zoomLevel": 1,
  "window.title": "${rootName} 👨🏻‍💻 ${separator}${activeEditorMedium}${dirty}",
  "sublimeTextKeymap.promptV3Features": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.formatOnPaste": false,
  "editor.tabSize": 2,
  "editor.fontFamily": "Fira Code",
  "editor.fontWeight": "300",
  "editor.fontLigatures": true,
  "editor.fontSize": 13,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "gitlens.codeLens.enabled": false,
  "gitlens.keymap": "chorded",
  "gitlens.advanced.messages": {
    "suppressCommitHasNoPreviousCommitWarning": false,
    "suppressCommitNotFoundWarning": false,
    "suppressFileNotUnderSourceControlWarning": false,
    "suppressGitVersionWarning": false,
    "suppressLineUncommittedWarning": false,
    "suppressNoRepositoryWarning": false,
    "suppressResultsExplorerNotice": false,
    "suppressShowKeyBindingsNotice": true
  },
  "cSpell.userWords": [
    "evenodd"
  ],
  "gitlens.historyExplorer.enabled": true,
  "workbench.colorTheme": "Atom One Dark",
  "diffEditor.ignoreTrimWhitespace": false,
  "workbench.editor.showTabs": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
}
```

# Snippets
```js
{
  "console.log": {
    "prefix": "cl",
    "body": "console.log('>>> $2', $1)"
  },
  "console.warn": {
    "prefix": "cw",
    "body": "console.warn('>>> $2', $1)"
  },
  "console.error": {
    "prefix": "cw",
    "body": "console.error('>>> $2', $1)"
  },
  "describe": {
    "prefix": "des",
    "body": "describe('$1', () => {\n  $2\n})"
  },
  "its": {
    "prefix": "its",
    "body": "it('should $1', () => {\n  $2\n})"
  },
  "expect": {
    "prefix": "ep",
    "body": "expect($1).$2"
  },
  "expect-match-object": {
    "prefix": "epm",
    "body": "expect($1).toMatchObject({\n  $2\n})"
  },
  "doc-render-doc": {
    "prefix": "drd",
    "body": "const doc = renderDoc()"
  },
  "render-doc": {
    "prefix": "rd",
    "body": "renderDoc()"
  }
}
```
# Extensions
- Atom One Dark
- ESLint
- GitLens
- Jest
- Sublime Text Keymap
- WakaTime

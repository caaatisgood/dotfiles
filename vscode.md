# User Settings

```js
{
  "editor.acceptSuggestionOnEnter": "smart",
  "editor.cursorBlinking": "expand",
  "editor.cursorStyle": "underline",
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.fontWeight": "300",
  "editor.hover.delay": 150,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.showSlider": "always",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.quickSuggestionsDelay": 0,
  "editor.renderLineHighlight": "all",
  "editor.snippetSuggestions": "top",
  "editor.tabSize": 2,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "telemetry.enableTelemetry": false,
  "terminal.integrated.fontSize": 14,
  "window.title": "${rootName} 👨🏻‍💻 ${separator}${activeEditorMedium}${dirty}",
  "window.zoomLevel": 0,
  "workbench.activityBar.visible": false
  "workbench.colorTheme": "Atom One Dark",
  "workbench.editor.enablePreview": false,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.editor.highlightModifiedTabs": true,
  "workbench.iconTheme": "vscode-icons",
  "workbench.sideBar.location": "right",
  "flow.useNPMPackagedFlow": true,
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
  "gitlens.codeLens.enabled": false,
  "gitlens.keymap": "chorded",
  "gitlens.views.fileHistory.enabled": true,
  "gitlens.views.lineHistory.enabled": true,
  "jest.runAllTestsFirst": false,
  "cSpell.ignoreWords": [
    "aasm",
    "angularjs",
    "backend",
    "blockchain",
    "classname",
    "dropdown",
    "filepicker",
    "filestack",
    "filestackcontent",
    "fontawesome",
    "fortawesome",
    "fullstack",
    "howitworks",
    "klass",
    "lazyload",
    "longterm",
    "mailto",
    "memoized",
    "mentorship",
    "mentee",
    "nbsp",
    "noopener",
    "noreferrer",
    "onboarding",
    "prefetch",
    "proxify",
    "reactjs",
    "reactnative",
    "repo",
    "rollbar",
    "signin",
    "signout",
    "signup",
    "typeform",
    "unfollow",
    "unmount",
    "unstar",
    "webapp",
    "worklog",
    "youtube",
    "visibilitychange",
    "xsmall"
  ],
  "cSpell.ignoreRegExpList": [
    "/btns?/",
    "/(C|c)odementor/",
    "/(C|c)tas?/",
    "/(R|r)e(c|C)aptcha/",
    "/mentees?/"
  ]
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

# User Settings

```js
{
  "editor.cursorBlinking": "expand",
  "editor.cursorStyle": "underline",
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.hover.delay": 150,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.showSlider": "always",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.quickSuggestionsDelay": 0,
  "editor.acceptSuggestionOnEnter": "smart",
  "editor.renderLineHighlight": "all",
  "editor.snippetSuggestions": "top",
  "editor.tabSize": 2,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "telemetry.enableTelemetry": false,
  "terminal.integrated.fontSize": 14,
  "window.title": "${rootName} 👨🏻‍💻 ${separator}${activeEditorMedium}${dirty}",
  "window.zoomLevel": 0,
  "workbench.activityBar.visible": false,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.editor.highlightModifiedTabs": true,
  "workbench.iconTheme": "material-icon-theme",
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
  "cSpell.ignoreWords": [
    "aasm",
    "angularjs",
    "backend",
    "blockchain",
    "classname",
    "dropdown",
    "expertises",
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
    "repos",
    "rollbar",
    "signin",
    "signout",
    "signup",
    "toggleable",
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
  ],
  "workbench.colorTheme": "Atom One Dark",
  "cSpell.enabledLanguageIds": [
    "asciidoc",
    "c",
    "cpp",
    "csharp",
    "css",
    "git-commit",
    "go",
    "handlebars",
    "haskell",
    "html",
    "jade",
    "java",
    "javascript",
    "javascriptreact",
    "json",
    "jsonc",
    "latex",
    "less",
    "markdown",
    "php",
    "plaintext",
    "pug",
    "python",
    "restructuredtext",
    "rust",
    "scala",
    "scss",
    "text",
    "typescript",
    "typescriptreact",
    "yaml",
    "yml"
  ],
  "workbench.editor.showTabs": true,
  "workbench.editor.enablePreview": false
}
```

# Snippets
```json
{
  "console.log": {
    "prefix": "cl",
    "body": "console.log('> $2', $1)"
  },
  "console.warn": {
    "prefix": "cw",
    "body": "console.warn('> $2', $1)"
  },
  "console.error": {
    "prefix": "cw",
    "body": "console.error('> $2', $1)"
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
  "expect-to-equal": {
    "prefix": "epe",
    "body": "expect($1).toEqual($2)"
  },
  "expect-to-have-length": {
    "prefix": "epl",
    "body": "expect($1).toHaveLength($2)"
  },
  "doc-render-doc": {
    "prefix": "drd",
    "body": "const doc = renderDoc()"
  },
  "react-pure-component": {
    "prefix": "rpc",
    "body": "import React from 'react'\nimport PropTypes from 'prop-types'\nimport styled from 'styled-components'\n\nconst $1 = () => (\n  <StyledContainer></StyledContainer>\n)\n\n$1.propTypes = {\n\n}\n\nexport default React.memo($1)\n\nconst StyledContainer = styled.div`\n`"
  },
  "render-doc": {
    "prefix": "rd",
    "body": "renderDoc()"
  },
  "it-should-render-node": {
    "prefix": "isrn",
    "body": "it('should render $1', () => {\n  const doc = renderDoc()\n  const node = doc.find('$1')\n  expect(node.props()).toMatchObject({$2})\n})"
  },
  "import-ui-kit-dialog": {
    "prefix": "impd",
    "body": "import Dialog from '@codementor/ui-kit/Dialog'\nimport DialogHeader from '@codementor/ui-kit/Dialog/DialogHeader'\nimport DialogBody from '@codementor/ui-kit/Dialog/DialogBody'\nimport DialogFooter from '@codementor/ui-kit/Dialog/DialogFooter'"
  },
  "eslint-disable-next-line react/prop-types": {
    "prefix": "ednlpt",
    "body": "// eslint-disable-next-line react/prop-types"
  }
}
```
# Extensions
- Atom One Dark
- Code Spell Checker
- colorize
- ESLint
- GitLens
- GraphQL for VSCode
- Jest
- Material Icon Theme
- Sublime Text Keymap
- stylelint
- WakaTime

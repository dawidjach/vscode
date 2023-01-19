# vscode
1. https://test.jaderbass.de/vs-code/
2. https://code.visualstudio.com/docs/getstarted/tips-and-tricks
3. https://code.visualstudio.com/docs/getstarted/themes
4. https://www.hmablogs.com/change-color-of-text-and-syntax-in-vscode-editor/
5. VS Code : Change Any Tag Color. Edit Custom Syntax Colors  (No extension) ->  https://www.youtube.com/watch?v=Su-cNLe0dgw
6. Spracheinstellung für z.B. Laravel: 
- https://github.com/Laravel-Lang/lang/releases
- z.B. C:\Users\User\laravel-gk-2\lang
7. Git user.name email:
- https://git-scm.com/book/de/v2/Git-einrichten-Git-Konfiguration
8. console log shortcut:
- strg + shift + p -> preferences open keyboard shortcuts (JSON) :
- 
{
  "key": "ctrl+shift+l",
  "command": "editor.action.insertSnippet",
  "when": "editorTextFocus",
  "args": {
    "snippet": "console.log('${TM_SELECTED_TEXT}$1')$2;"
  }
}

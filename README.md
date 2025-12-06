# PL/SQL Language Pack

Brings fast, lightweight, and accurate PL/SQL syntax highlighting and snippets to VS Code-compatible editors including **VS Code**, **Cursor**, **Windsurf**, **Antigravity**, and other **Code OSS builds** (via Open VSX).

## ✨ Features

-   **Accurate Highlighting**: Precisely highlights PL/SQL reserved words, data types, and built-in functions.
-   **Practical Snippets**: Includes ready-to-use snippets for common structures like packages, procedures, functions, and PL/Doc blocks.
-   **Broad File Support**: Works out of the box with all common Oracle file extensions (`.sql`, `.pck`, `.pkb`, `.trg`, `.vw`, and more).
-   **Lightweight**: No unnecessary extras—just the essentials for efficient PL/SQL editing.

![Preview](https://raw.githubusercontent.com/danilrez/ccm-oracle-plsql/refs/heads/master/images/Preview.png)

## 🚀 Install

1.  Open the [VS Marketplace page](https://marketplace.visualstudio.com/items?itemName=CrappyCodeMaker.ccm-plsql-oracle).
2.  Click **Install**, and your editor will automatically handle file associations for PL/SQL.
3.  To use custom file extensions, add a manual association in your `settings.json`:

```json
"files.associations": {
	"*.myplsql": "plsql-ccm",
	"*.sql": "plsql-ccm"
}
```

## ⚙️ Configuration

You can customize the extension by pointing it to your own JSON files for completions and PL/Doc generation.

-   `plsql-language.completion.path`: Path to a custom JSON file for identifier completions (see `snippets/plsql.completion.json` for an example).
-   `plsql-language.pldoc.path`: Path to a custom JSON file for the PL/Doc snippet (see `snippets/pldoc.json` for an example).

_**Pro Tip:** To prevent your customizations from being overwritten during updates, store your custom files in your project folder (or another safe place outside the extension directory) and point the settings to them._

For project-specific tweaks, you can also override the built-in snippets using the standard [VS Code snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets) feature.

## 💬 Feedback

Got questions or ideas? Feel free to [open an issue](https://github.com/danilrez/ccm-oracle-plsql/issues).

---

Made by **[Danil Reznichenko](https://github.com/danilrez)**. Enjoy coding! 🎉

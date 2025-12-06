# PL/SQL Language Pack for VS Code

Syntax highlighting, and ready-to-use snippets for Oracle PL/SQL.

## ✨ Features

-   Highlights PL/SQL reserved words, data types, and built-ins with tuned scopes
-   Snippets for packages, procedures, functions, and PL/Doc blocks
-   Supports common Oracle extensions out of the box (`.sql`, `.pck`, `.pkb`, `.trg`, `.vw`, and more)
-   Lightweight: ships only the grammar, snippets, and configuration needed for PL/SQL editing

![Preview](https://raw.githubusercontent.com/danilrez/ccm-oracle-plsql/refs/heads/master/images/Preview.png)

## 🚀 Install

1. Open the [VS Marketplace page](https://marketplace.visualstudio.com/items?itemName=CrappyCodeMaker.ccm-plsql-oracle).
2. Click **Install**. VS Code will associate PL/SQL-centric extensions automatically.
3. Using a custom extension? Add a manual association:

```json
"files.associations": {
	"*.myplsql": "plsql-ccm",
	"*.sql": "plsql-ccm"
}
```

## ⚙️ Configuration

-   `plsql-language.completion.path`: Path to a JSON file that drives identifier completions (see `snippets/plsql.completion.json`).
-   `plsql-language.pldoc.path`: Path to a JSON file defining the PL/SQL documentation snippet (see `snippets/pldoc.json`).

_Tip: keep your custom completion/PLDoc files outside the extension folder (e.g., in your project) and point the settings above to them; the bundled files are overwritten on update._

Override the bundled snippets via the standard VS Code snippets UI if you need per-project tweaks.

## 💬 Feedback

Questions or ideas? Open an issue: https://github.com/danilrez/ccm-oracle-plsql/issues

Made by **[Danil Reznichenko](https://github.com/danilrez)**. Enjoy coding! 🎉

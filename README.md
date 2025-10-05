# CrappyCodeMaker syntax highlighting for Oracle PL/SQL

This extension **enhances** the default syntax highlighting for **Oracle PL/SQL**

## ✨ Features

- Prioritises PL/SQL reserved words, data types, and built-ins for crisp highlighting
- Ships ready-to-use code snippets for packages, procedures, and documentation blocks
- Supports every common Oracle PL/SQL file extension out of the box
- Lightweight: only ships the grammar, snippets, and assets required by VS Code

![Preview](https://raw.githubusercontent.com/danilrez/ccm-oracle-plsql/refs/heads/master/images/Preview.png)

## 🚀 Install

1. Go to [![VS Marketplace Badge](https://img.shields.io/badge/VS%20Marketplace-2C94FC?logo=visualstudiocode&logoColor=fff&style=flat)](https://marketplace.visualstudio.com/items?itemName=CrappyCodeMaker.ccm-plsql-oracle).

2. Click on the ![Install Badge](https://img.shields.io/badge/Install-2C94FC?logo=visualstudiocode&logoColor=fff&style=flat) button.
3. The language is automatically associated with PL/SQL-centric extensions (such as `.sql`, `.pck`, `.pkb`, `.trg`, `.vw`, etc.). If you use a custom extension, add it manually:
    ```json
	"files.associations": {
		"*.myplsql": "plsql-ccm"
	}
    ```
4. Optional: tailor snippets or completion metadata by editing your local copies of the files referenced in the **Configuration** section below.
5. Enjoy! 🎉

## ⚙️ Configuration

- `plsql-language.completion.path`: Path to a JSON file that drives identifier completions. Use `snippets/plsql.completion.json` as a template.
- `plsql-language.pldoc.path`: Path to a JSON file that defines the PL/SQL documentation snippet. See `snippets/pldoc.json` for the default structure.

The bundled snippets (`snippets/plsql.snippets.json`) can be overridden via the standard VS Code snippets UI if you need to tweak the defaults per project.

## 💬 Feedback

We’d love to hear your thoughts! If you have suggestions or encounter issues, please open an **[![Issue Badge](https://img.shields.io/badge/Issue-2C94FC?logo=visualstudiocode&logoColor=fff&style=flat)](https://github.com/danilrez/ccm-oracle-plsql/issues)**.
Be nice and happy coding! 😉

---

> Authored by © **[Danil Reznichenko](https://github.com/danilrez)**

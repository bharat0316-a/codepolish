# 🧼 CodePolish

**CodePolish** is a Visual Studio Code extension that lets you **beautify** and **minify** HTML, CSS, JavaScript, JSON, and JSONL code with ease. Whether you want clean, readable code or compact, production-ready output — CodePolish handles it in one click.

![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/b1c836b5-b2e9-67df-b783-53ff04f83ff0.codepolish?label=VS%20Code%20Marketplace)
![License: MIT](https://img.shields.io/github/license/bharat0316-a/codepolish)
![GitHub Stars](https://img.shields.io/github/stars/bharat0316-a/codepolish?style=social)

---

## ✨ Features

- ✅ Beautify with `Alt + Shift + B`
- ✅ Minify via right-click context menu
- ✅ Supports:
  - 🟧 HTML
  - 🟦 CSS
  - 🟨 JavaScript
  - 🟩 JSON
  - 🟫 JSONL (line-delimited JSON)
- ✅ Auto-detects language and applies correct formatter
- ✅ Works offline after setup
- ✅ Lightweight and fast

---

## 🧪 Language Support

| Language   | Beautifier     | Minifier      |
|------------|----------------|----------------|
| HTML       | `js-beautify`  | whitespace trim |
| CSS        | `js-beautify`  | `clean-css`    |
| JavaScript | `js-beautify`  | `terser`       |
| JSON       | `JSON.stringify(..., null, 4)` | `JSON.stringify(...)` |
| JSONL      | line-by-line `JSON.stringify(..., null, 4)` | line-by-line `JSON.stringify(...)` |

---

## 🚀 Installation

### From VS Code Marketplace

1. Launch VS Code  
2. Go to Extensions (`Ctrl + Shift + X`)  
3. Search for **CodePolish**  
4. Click **Install**

### From Source (GitHub)

```bash
git clone https://github.com/bharat0316-a/codepolish.git
cd codepolish
npm install
npm run compile
```

Then press `F5` to launch a development window.

---

## ⚙️ Usage

### 🧼 Beautify

- Shortcut: Select the code → `Alt + Shift + B`
- Or: Right-click in editor → **Beautify Code**  

### 📦 Minify

- Select the code → Right-click in editor → **Minify Code**

You can also run both from the command palette (`Ctrl + Shift + P` → search "CodePolish").

---

## 🧠 Extension Commands

| Command                | Description                 |
|------------------------|-----------------------------|
| `codepolish.beautify`  | Beautifies the current file |
| `codepolish.minify`    | Minifies the current file   |

---

## 📁 Project Structure

```
codepolish/
├── src/
│   ├── extension.ts       # VS Code entry point
│   └── formatter.ts       # Format logic per language
├── out/                   # Compiled output
├── package.json           # Metadata and config
├── README.md              # This file
└── icon.jpg               # Extension icon
```

---

## 🧑‍💻 Development

```bash
npm install         # Install dependencies
npm run compile     # Compile TypeScript
npm run watch       # Watch & auto-recompile
```

- Press `F5` in VS Code to run the extension in a development window.

---

## 🖼 Preview

📸 GIFs and screenshots coming soon!  
Want to contribute one? [Open a PR or issue](https://github.com/bharat0316-a/codepolish/issues)

---

## 📝 License

CodePolish is open-source under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome!  

```bash
fork → clone → branch → commit → push → PR
```

[Open an issue](https://github.com/bharat0316-a/codepolish/issues) or submit a pull request to help improve the project.

---

## 👤 Author

Developed by [**Bharat**](https://github.com/bharat0316-a)  
📂 GitHub: [github.com/bharat0316-a/codepolish](https://github.com/bharat0316-a/codepolish)

---

> 🧼 Clean code. Always. Everywhere — now including HTML, CSS, JS, JSON, and JSONL.


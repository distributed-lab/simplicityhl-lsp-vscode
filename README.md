# simplicityhl-lsp-vscode

This extension provides [SimplicityHL language](https://simplicity-lang.org) support in VSCode.

---

## Requirements

For the extension to work properly, you must have the [language server](https://github.com/distributed-lab/simplicityhl-lsp)  executable available in your system `PATH`.

## Installation

The extension is available on the [Open VSX Registry](https://open-vsx.org/extension/distributed-lab/simplicityhl-lsp).

## Building from Source

To build the extension locally, ensure you have **npm** installed. Then run:

```bash
npm run install && npm run vsce-package
```

This will generate a `.vsix` package that you can install into VS Code:

```bash
code --install-extension simplicityhl-lsp-*.vsix
```


# Redblue Language Server Protocol (LSP) & IDE Tooling (b-ide)

The dedicated tooling repository for the **Redblue** programming language ecosystem.

## Components
1. **Language Server Protocol (b lsp)**: Standalone JSON-RPC LSP 3.17 daemon providing auto-completion, hover definitions, go-to-definition, document formatting, and live diagnostics.
2. **VS Code Extension**: Native client connecting to b lsp, semantic highlighting, snippet expansion, and test explorer.
3. **Debug Adapter Protocol (b dap)**: Interactive debugging interface for breakpoints, step over/into, fiber inspection, and variable watch.
4. **Syntax Grammars**: Formal TextMate and Tree-sitter grammars for Neovim, JetBrains, and GitHub syntax highlighting.

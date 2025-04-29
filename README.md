# codelens.nvim
show lsp reference count and last git commiter

![codelens](https://github.com/user-attachments/assets/44ee1ad1-b2e4-4093-aec2-3c65f213d277)

## 📦 Installation

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
    "edte/codelens.nvim",
    opts = {},
},
```


## 📝 Configuration
```lua
{
	-- Target Symbol Kinds to show lens information
	target_symbol_kinds = {
		SymbolKind.Function,
		SymbolKind.Method,
		SymbolKind.Interface,
		SymbolKind.Class,
		SymbolKind.Struct,
		SymbolKind.Variable,
		SymbolKind.Constant,
		SymbolKind.Constructor,
		SymbolKind.Namespace,
		SymbolKind.File,
		SymbolKind.Enum,
	}
}

```


## 🚀 Usage
just enjoy it

## 📄 Thanks
- [lsp-lens.nvim](https://github.com/VidocqH/lsp-lens.nvim)
- [symbol-usage.nvim](https://github.com/Wansmer/symbol-usage.nvim)

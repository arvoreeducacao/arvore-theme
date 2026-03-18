# 🌳 Árvore Theme

A color theme based on [Árvore](https://arvore.com.br)'s **Bonsai Design System**. Available for multiple IDEs, terminals, and agents.

## Variants

- **Árvore Light** — Clean, bright theme with teal accents on a soft white background
- **Árvore Dark** — Deep ocean dark theme with vibrant Bonsai colors

## Preview

| Role | Light | Dark |
|------|-------|------|
| Primary (Teal) | `#40CAB6` | `#66DCCE` |
| Functions (Blue) | `#4F81F1` | `#8DAEF6` |
| Keywords (Purple) | `#8764D8` | `#B29CE7` |
| Strings (Teal) | `#309385` | `#8DE5DA` |
| Constants (Orange) | `#FB673A` | `#FCA78D` |
| Types (Teal) | `#39AF9F` | `#66DCCE` |
| Interfaces (Lime) | `#7FC923` | `#B3E577` |

## Install

### From source

```bash
# VS Code
cp -r arvore-theme ~/.vscode/extensions/arvore-theme

# Kiro
cp -r arvore-theme ~/.kiro/extensions/arvore-theme
```

Restart your editor, then select the theme with `Cmd+K Cmd+T` (macOS) or `Ctrl+K Ctrl+T` (Linux/Windows).

### OpenCode

Copy the theme files to your OpenCode themes directory:

```bash
mkdir -p ~/.config/opencode/themes
cp agents/opencode/arvore-dark.json ~/.config/opencode/themes/
cp agents/opencode/arvore-light.json ~/.config/opencode/themes/
```

Then select it with `/theme` in the TUI, or set it in your `tui.json`:

```json
{
  "theme": "arvore-dark"
}
```

### Kitty

Copy the theme file and include it in your `kitty.conf`:

```bash
cp terminals/kitty/arvore-dark.conf ~/.config/kitty/
```

Then add to your `~/.config/kitty/kitty.conf`:

```
include arvore-dark.conf
```

Replace `arvore-dark` with `arvore-light` for the light variant.

### Ghostty

Copy the theme file to your Ghostty themes directory:

```bash
mkdir -p ~/.config/ghostty/themes
cp terminals/ghostty/arvore-dark ~/.config/ghostty/themes/
cp terminals/ghostty/arvore-light ~/.config/ghostty/themes/
```

Then set it in your `~/.config/ghostty/config`:

```
theme = arvore-dark
```

## License

[MIT](LICENSE)

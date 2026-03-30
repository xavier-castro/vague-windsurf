# Vague for Windsurf

A cool, dark, low contrast colorscheme for Windsurf. Pastel yet vivid, like a fleeting memory...

## About

Vague is a carefully crafted dark theme designed for developers who appreciate subtle elegance. With its low contrast pastel palette, it reduces eye strain while maintaining excellent readability and syntax highlighting.

## Installation

### From VSIX (Recommended)

1. Download the latest `.vsix` file from [Releases](https://github.com/vague-theme/vague-windsurf/releases)
2. In Windsurf, go to **Extensions** view (Cmd+Shift+X / Ctrl+Shift+X)
3. Click the `...` menu and select **Install from VSIX**
4. Select the downloaded `.vsix` file
5. The theme will be installed and ready to use

### Rebuild the VSIX

To publish an updated extension package from this repo:

```bash
npm run release:patch
```

This bumps the patch version in `package.json` and creates a new `.vsix` file in the project root. Then reinstall that new file from Windsurf using **Install from VSIX**.

### From Source

1. Clone this repository:

```bash
git clone https://github.com/vague-theme/vague-windsurf.git
```

1. Copy the `themes/vague-color-theme.json` file to your Windsurf extensions folder:
   - **macOS**: `~/.windsurf/extensions/`
   - **Windows**: `%USERPROFILE%\.windsurf\extensions\`
   - **Linux**: `~/.windsurf/extensions/`

2. Create a folder named `vague-theme.vague-windsurf-<version>` and place the theme files inside

## Activation

1. Open the Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Type `Color Theme` and select **Preferences: Color Theme**
3. Select **Vague** from the list

Or set it directly in your settings.json:

```json
{
  "workbench.colorTheme": "Vague"
}
```

## Color Palette

| Color      | Hex       | Usage                  |
| ---------- | --------- | ---------------------- |
| Background | `#141415` | Editor background      |
| Foreground | `#cdcdcd` | Primary text           |
| Comment    | `#606079` | Comments               |
| Keyword    | `#6e94b2` | Keywords, control flow |
| Function   | `#c48282` | Function names         |
| String     | `#e8b589` | Strings                |
| Number     | `#e0a363` | Numbers, constants     |
| Type       | `#9bb4bc` | Types, classes         |
| Property   | `#c3c3d5` | Object properties      |
| Parameter  | `#bb9dbd` | Function parameters    |
| Builtin    | `#b4d4cf` | Built-in functions     |
| Constant   | `#aeaed1` | Constants              |
| Operator   | `#90a0b5` | Operators              |
| Error      | `#d8647e` | Errors                 |
| Warning    | `#f3be7c` | Warnings               |
| Hint       | `#7e98e8` | Hints, info            |
| Success    | `#7fa563` | Success states         |
| Visual     | `#333738` | Selection background   |
| Line       | `#252530` | Active line, borders   |
| Inactive   | `#1c1c24` | Inactive elements      |

## Screenshots

_Coming soon_

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Thanks to contributors

- [Vague Theme Organization](https://github.com/vague-theme) - Original theme creators
- All contributors to the original [vague.nvim](https://github.com/vague-theme/vague.nvim) theme

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Related Projects

- [vague.nvim](https://github.com/vague-theme/vague.nvim) - Original Neovim theme
- [vague.vim](https://github.com/vague-theme/vague.vim) - Vim version
- [vague-zed](https://github.com/vague-theme/vague-zed) - Zed editor version
- [vague-kitty](https://github.com/vague-theme/vague-kitty) - Kitty terminal
- [vague-ghostty](https://github.com/vague-theme/vague-ghostty) - Ghostty terminal
- [vague-kde](https://github.com/vague-theme/vague-kde) - KDE Plasma
- [vague-yazi](https://github.com/vague-theme/vague-yazi) - Yazi file manager

---

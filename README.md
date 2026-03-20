# vscode-color-themes

Personal VS Code / Cursor color themes.

## Available Themes

- `vscode_gruvbox_black`: Gruvbox Black
- `vscode_cursor_black`: Cursor Black

## Example

### Gruvbox
![Gruvbox](gruvbox.png)

### Cursor
![Cursor](cursor.png)

## How to Build

Install [`vsce`](https://github.com/microsoft/vscode-vsce) if you haven't already:

```bash
npm install -g @vscode/vsce
```

Build a `.vsix` package from a theme directory:

```bash
cd vscode_gruvbox_black && vsce package
```

Replace the directory name with any other theme package in this repository when needed.

### Importing into VS Code / Cursor

1. Open the Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Run **Extensions: Install from VSIX...**
3. Select the generated `.vsix` file

## Credits, Disclaimer & Licenses

- **Gruvbox** color palette by [Pavel Pertsev (morhetz)](https://github.com/morhetz/gruvbox), licensed under the [MIT License](https://github.com/morhetz/gruvbox/blob/master/LICENSE).
- **Gruvbox Material** palette by [Sainnhe Park](https://github.com/sainnhe/gruvbox-material), based on Gruvbox and licensed under the [MIT License](https://github.com/sainnhe/gruvbox-material/blob/master/LICENSE).
- **Cursor** editor by [Anysphere](https://cursor.com). Default theme colors and UI references are property of Anysphere Inc.

This repository repackages upstream color palettes into standalone VS Code / Cursor themes. Original palette design, naming, and authorship remain with their respective upstream projects.

All licenses belong to the original authors of each color theme.

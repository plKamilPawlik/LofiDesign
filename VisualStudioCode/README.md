# Lofi Dark (Visual Studio Code theme concept)

**Lofi Dark** is a personal Visual Studio Code theme concept inspired by the
official **Dark**, **Dark+** and **Dark Modern** themes.

It reuses the original **token colors** from VS Code
[source code](https://github.com/microsoft/vscode/tree/main/extensions/theme-defaults/themes)
and applies a customized editor color scheme for a slightly different, minimal
_lofi_ look.

## ✨ Concept

This theme was created purely for personal use. The idea was to keep the syntax
highlighting exactly the same as the official Dark/Dark+/Dark Modern themes
while experimenting with the **editor background and UI colors**.

- **Token colors** -> identical to VS Code’s official themes
- **Editor/UI colors** -> customized to create a calmer, low-contrast "Lofi"
  feel

## 📂 Project structure

This folder contains:

- `builds/` -> preview extensions, not intended for distribution
- `themes/` -> theme source files (JSON based on VS Code’s dark themes)
- `settings/settings.json` → example configuration for a quickstart setup

## 🚫 Not for Marketplace

This project is not suitable for publishing to the Visual Studio Code
Marketplace because:

- It directly reuses Microsoft’s official theme files (`dark_vs.json`,
  `dark_plus.json`, `dark_modern.json`)
- Theme names directly reference their originals
- The icon uses the official VS Code logo (restricted by the
  [VS Code brand guidelines](https://code.visualstudio.com/brand))

Therefore, **this theme is only for personal use** (though others may explore it
if they wish).

## 🛠 Installation

If you want to _just_ try it out:

1. Download one of the `.vsix` files from `/builds` (preview builds only).
2. Install manually in VS Code via: or drag-and-drop onto the Extensions view.

⚠️ **Note**: These builds are **experimental and unofficial** — they are meant
only as a quickstart or demonstration, not a proper distribution.

## 📜 License

This project is a derivative of the **Visual Studio Code** source themes, which
are licensed under the [MIT License](https://opensource.org/licenses/MIT).

Therefore, the **Lofi Dark theme follows the same MIT License**. Please see the
included `LICENSE.txt` file from the VS Code repository for details.

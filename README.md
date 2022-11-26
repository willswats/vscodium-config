# VSCodium Config <!-- omit in toc -->

My VSCodium config.

## Table of Contents <!-- omit in toc -->

- [Installation](#installation)
  - [VSCodium flatpak](#vscodium-flatpak)
  - [VSCode flatpak](#vscode-flatpak)
  - [VSCodium](#vscodium)
  - [VSCode](#vscode)

## Installation

Add the `settings.json` and `keybindings.json` to your `config/VSCodium/User` directory.

Add the `product.json` to your `config/VSCodium` directory.

### VSCodium flatpak

To install the extensions, run these commands:

```bash
flatpak run com.vscodium.codium --install-extension ms-vscode.cpptools
flatpak run com.vscodium.codium --install-extension ms-dotnettools.csharp
flatpak run com.vscodium.codium --install-extension DigitalBrainstem.javascript-ejs-support
flatpak run com.vscodium.codium --install-extension dbaeumer.vscode-eslint
flatpak run com.vscodium.codium --install-extension olifink.fedora-gnome-light-dark
flatpak run com.vscodium.codium --install-extension ritwickdey.LiveServer
flatpak run com.vscodium.codium --install-extension sumneko.lua
flatpak run com.vscodium.codium --install-extension yzhang.markdown-all-in-one
flatpak run com.vscodium.codium --install-extension DavidAnson.vscode-markdownlint
flatpak run com.vscodium.codium --install-extension esbenp.prettier-vscode
flatpak run com.vscodium.codium --install-extension artdiniz.quitcontrol-vscode
flatpak run com.vscodium.codium --install-extension vscodevim.vim
```

### VSCode flatpak

Copy the commands from the [VSCodium flatpak](#vscodium-flatpak) section and replace `com.vscodium.codium` with `com.visualstudio.code`.

### VSCodium

Copy the commands from the [VSCodium flatpak](#vscodium-flatpak) section and replace `flatpak run com.vscodium.codium` with `codium`.

### VSCode

Copy the commands from the [VSCodium flatpak](#vscodium-flatpak) section and replace `flatpak run com.vscodium.codium` with `code`.

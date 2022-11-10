# VSCodium Config <!-- omit in toc -->

My VSCodium config.

## Table of Contents <!-- omit in toc -->

- [Installation](#installation)
  - [VSCodium flatpak](#vscodium-flatpak)
  - [VSCode flatpak](#vscode-flatpak)
  - [VSCodium](#vscodium)
  - [VSCode](#vscode)

## Installation

Add the `settings.json` and `keybindings.json` to your VSCodium or VSCode `User` directory.

### VSCodium flatpak

To install the extensions, run these commands:

```bash
flatpak run com.vscodium.codium --install-extension dsznajder.es7-react-js-snippets
flatpak run com.vscodium.codium --install-extension dbaeumer.vscode-eslint
flatpak run com.vscodium.codium --install-extension olifink.fedora-gnome-light-dark
flatpak run com.vscodium.codium --install-extension ritwickdey.LiveServer
flatpak run com.vscodium.codium --install-extension sumneko.lua
flatpak run com.vscodium.codium --install-extension yzhang.markdown-all-in-one
flatpak run com.vscodium.codium --install-extension DavidAnson.vscode-markdownlint
flatpak run com.vscodium.codium --install-extension esbenp.prettier-vscode
flatpak run com.vscodium.codium --install-extension artdiniz.quitcontrol-vscode
flatpak run com.vscodium.codium --install-extension vscodevim.vim
flatpak run com.vscodium.codium --install-extension Koihik.vscode-lua-format
flatpak run com.vscodium.codium --install-extension rangav.vscode-thunder-client
```

### VSCode flatpak

Copy the commands from the [VSCodium flatpak](#vscodium-flatpak) section and replace `com.vscodium.codium` with the id of the VSCode flatpak.

### VSCodium

Copy the commands from the [VSCodium flatpak](#vscodium-flatpak) section and replace `flatpak run com.vscodium.codium` with `codium`.

### VSCode

Copy the commands from the [VSCodium flatpak](#vscodium-flatpak) section and replace `flatpak run com.vscodium.codium` with `code`.

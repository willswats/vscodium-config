# VSCodium Config <!-- omit in toc -->

My VSCodium config.

## Table of Contents <!-- omit in toc -->

- [Installation](#installation)
  - [VSCodium](#vscodium)
  - [VSCodium flatpak](#vscodium-flatpak)
  - [VSCode flatpak](#vscode-flatpak)
  - [VSCode](#vscode)

## Installation

Add the `settings.json` and `keybindings.json` to your `config/VSCodium/User` directory.

Add the `product.json` to your `config/VSCodium` directory.

### VSCodium

To install the extensions, run these commands:

```bash
codium --install-extension rust-lang.rust-analyzer
codium --install-extension tamasfe.even-better-toml
codium --install-extension ms-vscode.cpptools
codium --install-extension ms-dotnettools.csharp
codium --install-extension DigitalBrainstem.javascript-ejs-support
codium --install-extension dbaeumer.vscode-eslint
codium --install-extension olifink.fedora-gnome-light-dark
codium --install-extension ritwickdey.LiveServer
codium --install-extension sumneko.lua
codium --install-extension yzhang.markdown-all-in-one
codium --install-extension DavidAnson.vscode-markdownlint
codium --install-extension esbenp.prettier-vscode
codium --install-extension artdiniz.quitcontrol-vscode
codium --install-extension vscodevim.vim
```

### VSCodium flatpak

Create a temporary alias and then run the commands in the [VSCodium](#vscodium) section:

```bash
alias codium="flatpak run com.vscodium.codium"
```

### VSCode flatpak

Create a temporary alias and then run the commands in the [VSCodium](#vscodium) section:

```bash
alias codium="flatpak run com.visualstudio.code"
```

### VSCode

Create a temporary alias and then run the commands in the [VSCodium](#vscodium) section:

```bash
alias codium="code"
```

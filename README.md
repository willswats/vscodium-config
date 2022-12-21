# VSCodium Config <!-- omit in toc -->

My VSCodium config.

## Table of Contents <!-- omit in toc -->

- [Add Settings](#add-settings)
- [Install Extensions](#install-extensions)
  - [VSCodium](#vscodium)
  - [VSCode](#vscode)
  - [VSCodium flatpak](#vscodium-flatpak)
  - [VSCode flatpak](#vscode-flatpak)

## Add Settings

1. Add the `product.json` to your `config/VSCodium` directory.
2. Add the `settings.json` and `keybindings.json` to your `config/VSCodium/User` directory.

## Install Extensions

### VSCodium

To install the extensions, run these commands:

```bash
codium --install-extension rust-lang.rust-analyzer
codium --install-extension tamasfe.even-better-toml
codium --install-extension dbaeumer.vscode-eslint
codium --install-extension olifink.fedora-gnome-light-dark
codium --install-extension ritwickdey.LiveServer
codium --install-extension sumneko.lua
codium --install-extension yzhang.markdown-all-in-one
codium --install-extension DavidAnson.vscode-markdownlint
codium --install-extension esbenp.prettier-vscode
codium --install-extension vscodevim.vim
```

### VSCode

Create an alias and then run the commands in the [VSCodium](#vscodium) section:

```bash
alias codium="code"
```

### VSCodium flatpak

Create an alias and then run the commands in the [VSCodium](#vscodium) section:

```bash
alias codium="flatpak run com.vscodium.codium"
```

The rust analyzer extension will not work without this flatpak override:

```bash
flatpak --user override com.vscodium.codium  --env=PATH=/app/bin:/usr/bin:/home/$USER/.cargo/bin
```

### VSCode flatpak

Create an alias and then run the commands in the [VSCodium](#vscodium) section:

```bash
alias codium="flatpak run com.visualstudio.code"
```

The rust analyzer extension will not work without this flatpak override:

```bash
flatpak --user override com.vscodium.codium  --env=PATH=/app/bin:/usr/bin:/home/$USER/.cargo/bin
```

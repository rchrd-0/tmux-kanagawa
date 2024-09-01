<h3 align="center">
	Kanagawa for <a href="https://github.com/tmux/tmux">tmux</a>
</h3>

<p align="center">
    A <a href="https://github.com/rebelot/kanagawa.nvim">Kanagawa</a> theme for tmux. Forked from <a href="https://github.com/catppuccin/tmux">Catppuccin/tmux</a>
</p>

## Content

1. [Themes](#themes)
1. [Installation](#installation)
1. [Overview](#overview)
1. [Configuration options](#configuration-options)

## Themes

- [Wave](./themes/kanagawa_wave.tmuxtheme)
- [Dragon](./themes/kanagawa_dragon.tmuxtheme)
- [Lotus](./themes/ka.tnagawa_lotus.tmuxtheme)

## Installation

In order to have the icons displayed correctly please use/update your favorite [patched font](https://www.nerdfonts.com/font-downloads).
If you do not have a patched font installed, you can override or remove any icon. Check the documentation below on the options available.

> Note: This fork is based on the [Catppuccin](https://github.com/catppuccin/tmux) tmux theme. Everything is the identical, except the colours which are based on the [Kanagawa](https://github.com/rebelot/kanagawa.nvim) nvim colourscheme.

### TPM

1. Install [TPM](https://github.com/tmux-plugins/tpm)
2. Add the Catppuccin plugin:

```bash
set -g @plugin 'rchrd-0/tmux-kanagawa'
# ...alongside
set -g @plugin 'tmux-plugins/tpm'
```

3. (Optional) Set your preferred flavor, it defaults to `"wave"`:

```bash
set -g @catppuccin_flavor 'dragon' # wave, dragon, lotus
```

### Manual

1. Clone this repository to your desired location (e.g.
   `~/.config/tmux/plugins/kanagawa`)
2. Add the following line to your `tmux.conf` file:
    `run ~/.config/tmux/plugins/kanagawa/kanagawa.tmux`
3. (Optional) Set your preferred flavor and/or add configuration options as
   listed in [Configuration Options](#configuration-options).
4. Reload Tmux by either restarting the session or reloading it with `tmux source-file ~/.tmux.conf`

## Overview

![Default](./assets/overview.png)
This is a diagram of how the theme is split between its components.

## Configuration options

All configuration options are can be found at [catppuccin/tmux](https://github.com/catppuccin/tmux). Just replace `catppuccin` with `kanagawa`.

## Credits

- [Catppuccin](https://github.com/catppuccin) and [catppuccin/tmux](https://github.com/catppuccin/tmux)
- [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) for the colourscheme
- [Nybkbox/tmux-kanagawa](https://github.com/Nybkox/tmux-kanagawa). Kanagawa for tmux but forked from [dracula/tmux](https://github.com/dracula/tmux)

&nbsp;

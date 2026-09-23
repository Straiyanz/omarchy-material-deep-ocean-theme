# Material Deep Ocean

Material Deep Ocean is a dark Omarchy theme with deep navy surfaces, cyan accents,
and a soft lavender lock screen.

## Origin

This theme adapts the Deep Ocean palette from Material Theme, originally
popularized as a Visual Studio Code theme. The included optional Neovim
configuration targets [Material.nvim](https://github.com/marko-cerovac/material.nvim)'s
`deep ocean` style, which is based on the same Material Theme colors.

Material Theme's public project is now succeeded by
[Vira Theme](https://github.com/vira-soft/vira-assets). This independent Omarchy
adaptation is not affiliated with either project.

## Installation

```sh
omarchy theme install https://github.com/Straiyanz/omarchy-material-deep-ocean-theme.git
omarchy theme set material-deep-ocean
```

## Compatibility

`colors.toml` uses Omarchy's semantic Quattro palette format. It supplies the
colors used to generate terminal, shell, editor, and application theme settings.

## Neovim

When installed with `omarchy theme install`, Omarchy treats this as a Git-installed
theme and ignores `neovim.lua` for safety. The file remains in this repository as
a reference and is not applied automatically.

Omarchy instead generates its Neovim theme configuration from `colors.toml`.
To use this repository's `material.nvim` configuration, manage it from your
local Neovim config or use a symlinked, user-owned theme worktree.

# Jellyfish for Omarchy

Jellyfish is an Omarchy theme package built to coordinate the wider desktop theme with the Neovim theme **`jellyfish`**.

This repo is the Omarchy-side theme bundle. It provides the files Omarchy uses for desktop and application styling, while Neovim itself is styled by the separate Neovim colorscheme named `jellyfish`.

## Relationship to the Neovim theme

This Omarchy theme is designed to pair with the Neovim theme:

- **Neovim theme name:** `jellyfish`
- **Omarchy theme repo:** `omarchy-jellyfish-theme`

Together they create a matching environment:

- Omarchy styles the system and supported apps
- Neovim loads `jellyfish`
- both use the same overall palette direction

## What this repo contains

Typical files include:

- `colors.toml`
- `colors.css`
- `btop.theme`
- `cava_theme`
- `chromium.theme`
- `mako.ini`
- `walker.css`
- `warp.yaml`
- `palette.json`

## How it works with Omarchy

This repo provides the Omarchy theme layer. Neovim should use the corresponding `jellyfish` colorscheme so the editor matches the rest of the setup.

## Naming convention

- **Omarchy repo:** `omarchy-jellyfish-theme`
- **Neovim theme:** `jellyfish`

## Goal

Jellyfish is meant to keep Omarchy, terminal tools, and Neovim visually consistent.

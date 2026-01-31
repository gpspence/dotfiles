# Dotfiles

Minimal personal dotfiles focused on a predictable Neovim workflow and sane defaults.
Designed to be portable, explicit, and safe to use on work machines.

## What’s here

* Neovim (Lua-based) config with lazy.nvim for plugin management
  * fzf-lua for navigation
  * Built-in LSP (Python, TypeScript, Bash, LaTeX)
* Bash config (.bashrc, .bash_alises, .bash_profile)
* Git config defaults
* Small quality-of-life defaults
* No secrets, tokens, or host-specific assumptions
* Optional tools are detected at runtime and degrade gracefully if missing.

## Managing & installing

These dotfiles are intended to be managed with chezmoi.

### Using chezmoi:

```
chezmoi init <repo>
chezmoi apply
```

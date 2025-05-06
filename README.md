# my dotfiles

my personal dotfiles managed with [chezmoi](https://www.chezmoi.io).

includes:
- `zsh` + Starship
- macOS & Linux support
- Carapace, fzf, eza, bat, ripgrep, etc.

## to install on a new machine

```bash
chezmoi init --ssh git@github.com:kybeka/dots.git
chezmoi apply

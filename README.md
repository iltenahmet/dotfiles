# dotfiles

Configs for use across machines: nvim, ghostty, tmux, zsh, opencode, kitty.

This repo is `~/.config`. `.gitignore` ignores everything else in that folder.

```
cd ~/.config
git init -b main
git remote add origin git@github.com:iltenahmet/dotfiles.git
git fetch origin
git checkout -f main
ln -sf ~/.config/zsh/zshrc ~/.zshrc
```

Secrets and machine-only shell settings go in `~/.config/zsh/local.zsh`, which git ignores.

# Neovim setup

## Install

- Iterm2
- Zsh (oh my zsh)
- fzf
- Ripgrep
- Fd
- Powerlevel 10k
- Tokyo Night Theme: https://github.com/rojadesign/iTerm2-Tokyo-Night-Color-Theme-by-rojadesign

## Links
- https://dev.to/immayurpanchal/unlocking-the-ultimate-productivity-mastering-iterm2-oh-my-zsh-powerlevel10k-fig-and-homebrew-1dih

## Tools

- Tmux (https://github.com/gpakosz/.tmux)
- Lazyvim (https://www.lazyvim.org/installation)

## .config/nvim/config/keymaps.lua

Add this line:
- vim.keymap.set('i', 'jk', '<esc>', { silent = true })k

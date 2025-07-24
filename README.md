# POCKET.NVIM
A minimal, portable Neovim configuration.
![](https://raw.githubusercontent.com/ch1ebak/pocket.nvim/refs/heads/main/screenshots/pocketnvim.png)


## Goal
- the entire config in one file
- plugins replaced with in-built features


## Features
- [x] sane defaults
- [x] treesitter
- [x] custom statusline
    - inspired by [Custom Neovim Statusline](https://nuxsh.is-a.dev/blog/custom-nvim-statusline.html)
- [x] custom tabline
    - matches the default neovim theme
- [x] transparency
- [ ] LSP
- [ ] better search

## Usage

### Clone as the main configuration
```
git clone --depth 1 https://github.com/ch1ebak/pocket.nvim ~/.config/nvim/
```

### Clone as a backup configuration
- Clone the repository to the .config folder.
```
git clone --depth 1 https://github.com/ch1ebak/pocket.nvim ~/.config/pocket.nvim/
```
- Launch
```
nvim --clean -u ~/.config/pocket.nvim/init.lua
```


## Why?
I was bored.

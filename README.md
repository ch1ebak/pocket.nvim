# POCKET.NVIM
A minimal, portable, Neovim configuration.
![](https://raw.githubusercontent.com/ch1ebak/pocket.nvim/refs/heads/main/screenshots/pocketnvim.png)


## About
> [!WARNING]
> TW: mentions of Emacs. I love it personally, but leaving a tw for anyone who might need it.

This is by no means a minimal config nor is it meant to be. I started this config because I wanted to see how many plugins I use could be replaced with Neovim's native functions. As it turns out, almost all of them.

Honestly, I feel like you can see that I used Emacs for years before I switched to Neovim. As they say, you can quit Emacs, but Emacs won't quit you (or at least I believe someone says that). What I mean to say is that the config is large and it's growing.


## Features
- [x] Sane defaults (according to me anyway)
- [x] Treesitter
- [x] Custom statusline
  - Inspired by [Custom Neovim Statusline](https://nuxsh.is-a.dev/blog/custom-nvim-statusline.html)
- [x] Custom tabline
  - Matches the default neovim theme
- [x] Transparency
- [X] Autoclose
- [x] LSP
  - [x] Lua-ls
  - [x] Harper
- [X] Completion
- [X] Snippets
- [x] Folding
- [X] Sessions
- [X] Better search
  - [x] Pretty much just this: [Custom Neovim Statusline](https://nuxsh.is-a.dev/blog/custom-nvim-statusline.html) 
  - [X] Works only on Nightly


## Requirements
- Neovim
- ripgrep
- fd


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

# or

NVIM_APPNAME=pocket.nvim nvim
```

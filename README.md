# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

### Stow

### fzf

### zoxide

### tree

### nvm

### pyenv

### [NvChad v2.0](https://github.com/NvChad/NvChad)
- `git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1`

## Installation

First, check out the dotfiles repo in your $HOME directory using git
```
$ git clone git@github.com/gunspartan/dotfiles.git
$ cd dotfiles
```
then use GNU stow to create symlinks
```
$ stow .
```

Then copy the nvim config to the nvim folder
```
~/.config/nvim/lua/custom/
```

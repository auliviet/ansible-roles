# Ansible Role - Dotfiles

Ansible role to install dotfiles on MacOS and Debian.

## Configurations

The dotfiles include configurations for:
- Git
- iTerm
- Tmux
- Vim
- VSCodium
- ZSH

## Source repository

This roles uses dotfiles hosted on Github:
[Auliviet's Dotfiles](https://github.com/auliviet/dotfiles)

## Getting started
1. Edit the variables used by this role:
    - `dotfiles_home`: path where the symlink will be added (default: ~)
    - `dotfiles_remote_repo`: url of the git repository of dotfiles (default: github.com/auliviet.dotfiles.git)
    - `dotfiles_local_repo`: path where the dotfiles directory will be copied (default: ~/.dotfiles)
    - `dotfiles_files`: list of dotfiles confing that will be symlinked in the dotfiles_home repository
    - `dotfiles_aliases`: list of files with zsh aliases

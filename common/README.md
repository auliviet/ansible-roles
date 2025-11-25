# Ansible Role - Common

Default list of packages to be installed on all MacOs and Linux machines.

## Packages included

- Git
- Vim
- Tmux
- Zsh

## Getting started
This role uses the default package manager on the OS (Homebrew for MacOS and APT for Debian). 
Ensure the package managers are installed.
1. Edit the list of packages in your playbook using the variable `common_packages`
2. Include this role in your playbook

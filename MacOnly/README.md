# MacOnly Dotfiles Setup

This directory contains configuration files (`dotfiles`) specifically for setting up a development environment on macOS using iTerm, ZSH, and Git. These files help configure your terminal, version control, and other essential tools to improve your workflow.

## Table of Contents
- [Introduction](#introduction)
- [Files Overview](#files-overview)
  - [.gitconfig](#gitconfig)
  - [.gitignore](#gitignore)
  - [.zshrc](#zshrc)
  - [config.sh](#configsh)
- [Setup Instructions](#setup-instructions)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Introduction
These dotfiles allow for easy configuration of your macOS development environment. The setup includes:
- **iTerm** configuration using ZSH as the shell.
- **Git** configurations for global `.gitignore` and `.gitconfig`.
- A custom shell script (`config.sh`) for initializing the environment.

## Files Overview

### .gitconfig
The `.gitconfig` file contains global Git configuration settings, such as your name and email for Git commits, preferred merge and diff tools, and some useful aliases.

### .gitignore
This global `.gitignore` file specifies file types and patterns to be ignored in every Git repository on your machine. It includes common patterns like `.DS_Store`, `.env` files, etc.

### .zshrc
The `.zshrc` file is the configuration file for ZSH, which runs when your terminal starts. It includes various shell settings, aliases, and environment variables to customize your terminal experience. You can add plugins such as `oh-my-zsh` to enhance functionality.

### config.sh
The `config.sh` script is used to set up the terminal environment. It can include commands to install Homebrew packages, configure macOS preferences, and initialize development tools. You can modify this script to fit your custom development setup.

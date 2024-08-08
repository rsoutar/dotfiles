# My Dotfiles

Welcome to my personal dotfiles repository. This repository contains configuration files and scripts to set up my development environment across different machines using GNU Stow.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Available Configurations](#available-configurations)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Dotfiles are plain text configuration files on Unix-y systems for customizing system and application behavior. This repository includes my configurations for various tools and applications, managed using GNU Stow.

## Prerequisites

Before you begin, ensure you have GNU Stow installed on your system. You can install it using your package manager:

- On Ubuntu/Debian:
  ```sh
  sudo apt-get install stow
  ```
- On macOS (using Homebrew):
  ```sh
  brew install stow
  ```

## Installation

To set up these dotfiles on your system, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/rsoutar/dotfiles.git ~/.dotfiles
   cd ~/.dotfiles
   ```

2. **Use Stow to symlink the configurations:**

   To install all configurations at once, use:

   ```sh
   stow .
   ```

   This command will stow everything in the current directory.

   Alternatively, if you want to install specific configurations, you can use:

   ```sh
   stow [package_name]
   ```

   Replace `[package_name]` with the name of the configuration you want to install (e.g., `vim`, `zsh`, `git`).

## Available Configurations

This repository includes configurations for:

- Shell (Bash/Zsh)
- Vim/Neovim
- Git
- Tmux
- [List any other tools or applications you have configurations for]

Each configuration is organized in its own directory within the repository.

## Usage

After installation, the configurations will be symlinked to your home directory. You can start using your customized environment right away.

For example:

- Open your terminal to see the shell configuration.
- Open Vim/Neovim to see the editor configuration.
- Use Git to see the Git configuration.

## Customization

You can customize these dotfiles to suit your preferences:

1. Navigate to the appropriate directory in the repository (e.g., `~/.dotfiles/vim/` for Vim configurations).
2. Edit the configuration files as needed.
3. The changes will be reflected immediately due to the symlinks created by Stow.

Feel free to explore and modify the files in this repository to better fit your workflow.

## Contributing

If you have suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

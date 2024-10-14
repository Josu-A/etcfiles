# Etcfiles

This repository ccontains my personal etc configuration files for various tools and applications.

## Installation

To install these etcfiles, you can clone the repository and create a bare repository with it if you want to keep track of your changes:

```console
$ cd /etc
# git clone https://github.com/Josu-A/etcfiles.git
$ cd $HOME
$ git --git-dir=$HOME/.etcfiles/ config --local status.showUntrackedFiles no
$ git --git-dir=$HOME/.etcfiles --work-tree=/etc checkout -f
```

## Usage

After installing the etcfiles, the easiest way to start using them is to reboot.

You can use the `etcfiles` alias to easily add, commit and push changes to the files.

Check out my [Dotfiles](https://github.com/Josu-A/dotfiles).

## Customization

Feel free to customize these dotfiles to suit your needs. You can edit the files directly or create additional configuration files as needed.

## Contributing

If you have any improvements or suggestions, please feel free to open an issue or submit a pull request.

## License

The repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

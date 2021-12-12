# dotfiles

`dotfiles` is a literate programming repository for my
[dotfiles](https://en.wikipedia.org/wiki/Hidden_file_and_hidden_directory#Unix_and_Unix-like_environments), including the following (so far):

- `~/.emacs.d/init.el` - GNU/Emacs.
- `~/.config/stumpwm/config` - STUMPWM.
- `~/.mednafen/mednafen.cfg` - Mednafen.
- `~/.sbclrc` - SBCL and Quicklisp.
- `~/.config/common-lisp/source-registry.conf.d/main.conf` - ASDF.
- `~/.config/mc/ini` - Midnight Commander.
- `~/.mikmodrc` - MikMod.
- `~/.gitconfig` - Git.
- `~/.ssh/config` - SSH.

## Installation

If You want to create a tangled (production-ready) version of the
website with this repo, clone it locally. Open the `dotfiles.org` file
in GNU/Emacs, and type `C-c C-v t` to tangle all of the files into
their correct places (**NOTE: THIS WILL OVERWRITE YOUR CURRENT
CONFIGURATION. BACKUP FIRST!**).

## Usage

The main utility for this repo is to make it easy for me to maintain
configurations across multiple machines. If it can be useful for You,
great. If not, that's fine, it's mostly just for me.

## Contributing
Pull requests are not welcome; Configuration is too personal a choice for such things.

## License
[AGPL](https://choosealicense.com/licenses/agpl/)

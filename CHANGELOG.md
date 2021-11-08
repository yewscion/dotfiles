# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased][srht]
<!-- Added, Changed, Removed, Fixed -->
### Added
- `cdr:make-lisp-project` generator function added to `~/.emacs.d/init.el`.
- `~/.Xresources` file support.
### Changed
- STUMPWM now using urxvt by default, as well as F11 fullscreen.

## [1.0.0] - 2021-11-07
### Added
- Standard Project Files, Including:
    - This `CHANGELOG.md` file, to document updates to the project.
    - A `LICENSE` file, to make it clear that this project is under
      [the AGPL][agpl].
    - A `README.md` file, to act as the front page my the repo on its
      [Sourcehut][srht] page.
    - An `AUTHORS` file, to document those who have contributed
      directly to this project.
- `dotfiles.org` supporting the following files:
     - `~/.emacs.d/init.el` - GNU/Emacs.
     - `~/.config/stumpwm/config` - STUMPWM.
     - `~/.mednafen/mednafen.cfg` - Mednafen.
     - `~/.sbclrc` - SBCL and Quicklisp.
     - `~/.config/common-lisp/source-registry.conf.d/main.conf` - ASDF.
     - `~/.config/mc/ini` - Midnight Commander.
     - `~/.mikmodrc` - MikMod.
     - `~/.gitconfig` - Git.
     - `~/.ssh/config` - SSH.


[1.0.0]: https://git.sr.ht/~yewscion/dotfiles/refs/v1.0.0
[agpl]: https://www.gnu.org/licenses/agpl-3.0.html
[srht]: https://sr.ht/~yewscion/dotfiles/

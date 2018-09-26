# vim-meson: Vim plugin for Meson

This repository contains the Vim plugin files in the Meson repository [1]
extracted with git-filter-branch [2] [3] in order to preserve the upstream
history.

If you want to pull updates directly from upstream Meson, then use the script
in the 'meta' branch.

## Overview

ftdetect sets the filetype
syntax does Meson syntax highlighting
plugin does Meson indentation

## Installation (Vim >= 8.0)

Clone this repo into Vim's 'packpath'. On Linux, assuming the default
'packpath', the following command will work:

    $ git clone https://github.com/chadversary/vim-meson ~/.vim/pack/whatever/start/meson

For more details, see topic 'packages' [4] in the Vim manual.

## Installation (Vim >= 7.0)

If you don't have a preferred installation method, one option is to install Tim
Pope's pathogen [5]. If your OS lacks a package for pathogen, you can install
it like so:

    $ git clone https://github.com/tpope/vim-pathogen ~/.vim/bundle/pathogen
    $ ln -sr ~/.vim/bundle/pathogen/autoload/pathogen.vim ~/.vim/autoload/pathogen.vim
    $ echo 'execute pathogen#infect()' >> ~/.vim/vimrc

Then install this repo as a pathogen plugin:

    $ git clone https://github.com/chadversary/vim-meson ~/.vim/bundle/meson

## References

[1]: https://github.com/mesonbuild/meson
[2]: man:git-filter-branch(1)
[3]: https://git-scm.com/docs/git-filter-branch
[4]: http://vimhelp.appspot.com/repeat.txt.html#packages
[5]: https://github.com/tpope/vim-pathogen

# wal.vim

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)

A vim colorscheme for use with **[pywal](https://github.com/dylanaraps/pywal)**.

![alt text](https://github.com/brainfucksec/wal.vim/blob/master/screenshot.png)

Including bundled themes for [lightline.vim](https://github.com/itchyny/lightline.vim) and [vim-airline](https://github.com/vim-airline/vim-airline).


## Installation

`wal.vim` can be installed for all platforms and the various variants/forks of Vim, Neovim in a uniform way. The recommended manager is [vim-plug](https://github.com/junegunn/vim-plug), but any other manager like [pathogen](https://github.com/tpope/vim-pathogen) or [Vundle](https://github.com/VundleVim/Vundle.vim) can also be used.


### Install with [vim-plug](https://github.com/junegunn/vim-plug):

    1. add `Plug 'brainfucksec/wal.vim'` to your [`vimrc`](https://vimhelp.org/usr_05.txt.html#vimrc-intro) within _vim-plug_'s plugin loading function
    2. run the `:PlugInstall` command in Vim
    3. activate the theme by adding `colorscheme wal` to the [vimrc](https://vimhelp.org/usr_05.txt.html#vimrc-intro) or change it on-the-fly by running `:colorscheme wal`

### Manual Installation:

    1. [Download the latest version](https://github.com/brainfucksec/wal.vim/archive/master.zip) or clone the repository:

        ```bash
        git clone https://github.com/brainfucksec/wal.vim
        ```

    2. Copy the git folder to your `vim/neovim` plugins folder:
        ```bash
        vim:

        cp -Rv wal.vim ~/.vim/pack/plugins/start/

        neovim:

        cp -Rv wal.vim ~/.local/share/nvim/site/pack/plugins/start/
        ```


**Please note that the plugin is in [beta version](https://github.com/brainfucksec/wal.vim/commit/07750d83b51224709c93f6919f75a524a71ca6d0) and has not been tested with all languages, I invite you to report improvements to be made**.

Happy coding :)

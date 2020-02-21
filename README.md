# wal.vim

## [pywal](https://github.com/dylanaraps/pywal) module: colorscheme for [vim](https://www.vim.org/), [neovim](https://neovim.io/).

See: https://github.com/dylanaraps/pywal/wiki/Customization#vim

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)


![alt text](https://github.com/brainfucksec/wal.vim/blob/master/screenshot.png)

Including bundled themes for [lightline.vim](https://github.com/itchyny/lightline.vim) and [vim-airline](https://github.com/vim-airline/vim-airline).


## Installation

`wal.vim` can be installed for all platforms and the various variants/forks of Vim, Neovim in a uniform way. The recommended manager is [vim-plug](https://github.com/junegunn/vim-plug), but any other manager like [pathogen](https://github.com/tpope/vim-pathogen) or [Vundle](https://github.com/VundleVim/Vundle.vim) can also be used.


### Install with [vim-plug](https://github.com/junegunn/vim-plug):

1. add `Plug 'brainfucksec/wal.vim'` to your [`vimrc`](https://vimhelp.org/usr_05.txt.html#vimrc-intro) within _vim-plug_'s plugin loading function

2. run the `:PlugInstall` command in Vim

3. activate the theme by adding `colorscheme wal` to the [vimrc](https://vimhelp.org/usr_05.txt.html#vimrc-intro) or change it on-the-fly by running `:colorscheme wal`

### Manual Installation:

1. [download the latest version](https://github.com/brainfucksec/wal.vim/archive/master.zip) or clone the repository:

```bash
git clone https://github.com/brainfucksec/wal.vim
```

2. copy the git folder to your `vim/neovim` plugins folder:

```vim
cp -Rv wal.vim ~/.vim/pack/plugins/start/
```

3. activate the theme as written above.


**Neovim users, make sure to remove [`set termguicolors`](https://github.com/dylanaraps/wal.vim/issues/3) as it messes up the colorscheme.**


**Please note that the plugin is in [beta version](https://github.com/brainfucksec/wal.vim/commit/07750d83b51224709c93f6919f75a524a71ca6d0) and has not been tested with all languages, I invite you to report improvements to be made**.

Happy coding :)

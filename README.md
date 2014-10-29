marshallmick's vim configuration
==========================

Edited fork of [Mislav's](https://github.com/mislav/vimfiles) vim
configuration

Thanks to these guys:

* [Mislav](]https://github.com/mislav/vimfiles)
* [Gary Bernhardt](http://destroyallsoftware.co m),
* [Drew Neil](http://vimcasts.org),
* [Tim Pope](http://tbaggery.com),
* and the [Janus project](https://github.com/carlhuda/janus).

My configuration uses [Pathogen](https://github.com/tpope/vim-pathogen) and git submodules.

## Installation:

Prerequisites: git.

1. Move your existing configuration somewhere else:  
   `mv .vim* .gvim* my_backup`
2. Clone this repo into ".vim":  
   `git clone https://github.com/marshallmick007/vimfiles ~/.vim`
3. Go into ".vim" and run "rake":  
   `cd ~/.vim && rake`

This will install "~/.vimrc" and "~/.gvimrc" symlinks that point to
files inside the ".vim" directory.

## Features:

* 2 spaces, no tabs
* Autoclose parens and brackets complements of autoclose.vim
* incremental, case-insensitive search
* 'Leader' character mapped to "," (comma)
* `,f` opens file search via :CtrlP plugin
* `,b` opens easybuffer in a horizontal buffer
* `,,` switches between two last buffers
* `<C-j/k/h/l>` switches between windows (no need to prepend `<C-w>`)

## Plugins:

* ack
* [CtrlP](https://github.com/kien/ctrlp.vim)
* commentary
* endwise
* fugitive
* markdown
* rails
* haml
* scss
* coffee-script
* autoclose
* powerline w/custom Menlo Regular font
* [snipmate](http://www.vim.org/scripts/script.php?script_id=2540)
* [easybuffer](https://github.com/troydm/easybuffer.vim)

_updated 10/4/2012_

=================
Orignal Project: Powerline for vim
=================

:Author: Kim Silkebækken (kim.silkebaekken+vim@gmail.com)
:Source: https://github.com/Lokaltog/vim-powerline
:Version: β

Plugin is currently in maintenance mode, no feature requests will be accepted.
Vim-powerline will be deprecated in favour of https://github.com/Lokaltog/powerline once it is ready.


Installation
------------

Here's what I had to do to install on OSX latest using iterm2 

1. Install a patched font to use. I included a few of them the fontpatcher directory.  Open one of the `*-Powerline.ttl` files, install, then set that as your font in iterm preferences or see original powerline repo README for how to patch another font.

2. add to vimrc (I use command line vim, it probably works with macvim/gvim too):

    " Powerline status line
    let g:Powerline_symbols = 'fancy'
    let g:Powerline_colorscheme = 'default'
    set t_Co=256
    set laststatus=2

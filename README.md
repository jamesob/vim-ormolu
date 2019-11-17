vim-ormolu
==========

Introduction
------------

This is a plugin to integrate [ormolu] into your vim workflow. It will run
ormolu on Haskell buffers every time they are saved similar to how `gofmt`. It
requires ormolu be accessible from your `$PATH`.

If you have a non-standard `$PATH` then set `g:ormolu_command` Vim variable to
the location of the ormolu binary.

The specific flags for Ormolu can be configured by changing the Vim variable
`g:ormolu_command`.

[ormolu]: https://github.com/tweag/ormolu

Installation
------------

  $ stack install ormolu
  $ cd ~/.vim/bundle -- vim
  $ cd ~/.config/nvim/bundle -- neovim
  $ git clone https://github.com/sdiehl/vim-ormolu.git

This plugin is compatible with [Vundle.vim] and [pathogen.vim].

[Vundle.vim]: https://github.com/gmarik/Vundle.vim
[pathogen.vim]: https://github.com/tpope/vim-pathogen

License
-------

MIT License
Copyright (c) 2019, Stephen Diehl

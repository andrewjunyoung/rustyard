# Rustyard

<p align="center">Elegant | Retro | Powerful</p>
<p align="center">Dark <a href="http://www.vim.org">Vim</a> color theme for a
flawless clear workflow.</p>

<p align="center">Based on the Rustyard color palette.</p>

<!-- vim-markdown-toc GFM -->

* [Abstract](#abstract)
* [Philosophy](#philosophy)
* [Installation](#installation)
  * [Manual](#manual)
  * [Using a plugin manager](#using-a-plugin-manager)

<!-- vim-markdown-toc -->

## Abstract

Rustyard is a dark Vim theme developed gradually through experimentation guided
by its philosophy. Rustyard aims to be a clean dark theme based off the Rustyard
[color palette]() <!-- TODO --> which incoroprates clear semantic coloring and
high contrast to make a crisp, high-readability color theme.

The color theme and composure is designed to give a retro feel, inspired in part
by aztec color palettes, and works across different file extensions and with
different plugins.

## Philosophy

* Colors segregated by semantics.
  * Similar semantic components are highlighted with similar colors.
  * Fine-grained color differentiation so you know if the number you typed is an
    int or a float to your parser.
* Color balance
* High contrast

## Installation

### Manual

Download the latest version, or clone the [git
repository](https://github.com/andrewjunyoung/rustyard). <!-- TODO -->

### Using a plugin manager

Put the following into your `.vimrc` (`init.vim` if you use neovim):

* [`vim-plug`](https://github.com/junegunn/vim-plug)
```vim
Plug 'andrewjunyoung/rustyard'
```

Then run `:PlugInstall`.

* [`pathogen`](https://github.com/tpope/vim-pathogen):

```sh
cd ~/.vim/bundle
git clone git://github.com/andrewjunyoung/rustyard
```

* [`Vundle`](https://github.com/VundleVim/Vundle.vim):

```vim
Plugin 'andrewjunyoung/rustyard'
```

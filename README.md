# Intro

This is a mirror of http://www.vim.org/scripts/script.php?script_id=39

The matchit.vim script allows you to configure % to match more than just
single characters.  You can match words and even regular expressions.
Also, matching treats strings and comments (as recognized by the
syntax highlighting mechanism) intelligently.

The default ftplugins include settings for several languages:
Ada, ASP with VBS, Csh, DTD, Essbase, Fortran, HTML, JSP
(same as HTML), LaTeX, Lua, Pascal, SGML, Shell, Tcsh, Vim, XML.
(I no longer keep track, so there may be others.)

For more details, try `:help matchit` in Vim.
The help documentation explains how to configure the script for
a new language and how to modify the defaults.

**NOTE:** Since vim 6.0, matchit.vim has been included in the standard
vim distribution, under the macros/ directory;

The version here may be more recent, and easy for user to download and
manage by plugin-managers

## Requirements

- Vim 6.0 or higher.

## Installation

This plugin follows the standard runtime path structure, and as such it can
be installed with a variety of plugin managers:

### Install using [Pathogen](https://github.com/tpope/vim-pathogen):

    cd ~/.vim/bundle
    git clone https://github.com/Firef0x/matchit.git

### Install using [Vundle](https://github.com/gmarik/Vundle.vim):

    # add this line to your .vimrc file
    Plugin 'Firef0x/matchit'

### Install using [NeoBundle](https://github.com/Shougo/neobundle.vim):

    # add this line to your .vimrc file
    NeoBundle 'Firef0x/matchit'

### Install manually

Download [zip file](https://github.com/Firef0x/matchit/archive/master.zip):

    cd ~/.vim
    unzip matchit-master.zip

copy all of the files into your ~/.vim directory,
then execute `:helptags` in Vim to refresh help tags.

My Vim Setup
=============

This is my personal Vim setup. Vim is a great editor and one of its great features
is that you can easly share your config file on many different servers/desktops
and be sure that Vim will behave the same everywhere.

Installation
-------

Simply clone this repo using:

    $ cd ~
    $ git clone git://github.com/mifo/vim-config.git

Then execute these commands from your home directory:

    $ mv vim-config .vim
    $ ln -sf .vim/_vimrc .vimrc

Then you can install my favorite plugins using:

    $ cd ~/.vim/bundle
    $ rake plugins:install

I use pathogen to manage my plugins, so in this way I'm sure that I use
the latest versions available.

To update all plugins, simply call:

    $ cd ~/.vim/bundle
    $ rake plugins:update

Feel free to edit the Rakefile in ~/.vim/bundle and add your own favorite Vim plugins.
Also note that my config may be not the best fit for your typing style, so feel free
to remove everything, just keep the pathogen inflect function ;-)

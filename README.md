# Dotfiles

My dotfiles 👌🚀

## Install

Install [rcm](https://github.com/thoughtbot/rcm):

    brew tap thoughtbot/formulae
    brew install rcm

Install the dotfiles:

    git clone https://github.com/Fridus/dotfiles.git $HOME/dotfiles
    cd $HOME/dotfiles && git submodule update --init --recursive
    env RCRC=$HOME/dotfiles/rcrc rcup

# Inspirations

- https://github.com/LoicMahieu/dotfiles
- https://github.com/jfrazelle/dotfiles

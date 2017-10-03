# Dotfiles

My dotfiles 👌🚀

## Install

Install [rcm](https://github.com/thoughtbot/rcm):

    brew tap thoughtbot/formulae
    brew install rcm

Install `antigen`

    brew install antigen

Install the dotfiles:

    git clone https://github.com/Fridus/dotfiles.git $HOME/dotfiles
    cd $HOME/dotfiles && git submodule update --init --recursive
    env RCRC=$HOME/dotfiles/rcrc rcup


## iTerm 2 🖥
https://www.iterm2.com

```
Preference > General > Load Preference from folder or URL:
~/dotfiles/iterm2
```


## External dependencies

### brew/apt

```
cdrtools
docker-compose
docker-machine
docker-machine-driver-xhyve
git
git-extras
lnav
tree
watch
wget
```

### npm

```
airpaste
airtar
bower
bower-check-updates
node-inspector
npm-check-updates
serve
```


## Inspirations

- https://github.com/LoicMahieu/dotfiles
- https://github.com/jfrazelle/dotfiles

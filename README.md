## Restore your Dotfiles

* Install git
* Clone your dotfiles repository `git clone [your repository of dotfiles] $HOME/.dotfiles`
* Go to your dotfiles folder `cd $HOME/.dotfiles`
* Install git submodules `git submodule update --init --recursive`
* Install your dotfiles `DOTFILES_PATH="$HOME/.dotfiles" DOTLY_PATH="$DOTFILES_PATH/modules/dotly" "$DOTLY_PATH/bin/dot" self install`
* Restart your terminal
* Import your packages `dot package import`


# For this config you need: 

## External dependencies for VIM
* Node > 8. Use nvm whenever possible (https://github.com/nvm-sh/nvm)
* https://github.com/ggreer/the_silver_searcher
* https://github.com/BurntSushi/ripgrep#installation

## Recommendation
* https://github.com/aykamko/tag
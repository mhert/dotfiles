# mhert/dotfiles

## Usage

```
echo "export DOTFILES=~/dotfiles\nsource \$DOTFILES/profile" >> ~/.zprofile
echo "export DOTFILES=~/dotfiles\nsource \$DOTFILES/rc" >> ~/.zshrc
echo "[include]\n    path = ~/dotfiles/gitconfig" >> ~/.gitconfig
mkdir -p ~/.gnupg && ln -s ~/dotfiles/gpg.conf ~/.gnupg/gpg.conf 
```

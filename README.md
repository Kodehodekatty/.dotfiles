# .dotfiles


```bash
sudo apt install zsh
sudo apt install stow
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
cd .dotfiles
stow .
fc-cache -rv
```
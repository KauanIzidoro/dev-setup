# [ZSH Setup](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH) 

> Update

```bash
sudo pacman -Syu
```

> Install on Arch Linux

```bash
pacman -S zsh
```
> Install `curl` for continue

```bash
pacman -S curl
```
> Install `Oh-my-zsh`:

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
#### Now you should check if the .zshrc file is created on your system. This file is config file of ZSH 

> Change terminal theme:

```bash
11 ZSH_THEME="norm"
```
> Add plugins: 

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/zdharma/zinit/master/doc/install.sh)"
```
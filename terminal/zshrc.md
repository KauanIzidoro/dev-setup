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

> Install `tree`:
```bash
sudo pacman -S tree
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

- `zsh-autosuggestion`:

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

- `zsh-syntax-highlighting`:

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

- Others plugins:

```bash
73 plugins=(git web-search zsh-autosuggestions zsh-syntax-highlighting)
```

- Reload system:

```bash
source ~/.zshrc
```

> Set alias in `.zshrc` file:

```bash 
alias c='clear'
alias ct='clear && tree'
alias t='tree'
alias gfp='git fetch && git pull'
alias gss='git status'
alias cl='clear && ls'
alias update='sudo pacman -Syu && sudo pacman -Sc && sudo pacman -Rns $(pacman -Qtdq)'
``` 
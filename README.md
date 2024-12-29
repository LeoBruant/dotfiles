# dotfiles

## Disclaimer

This theme is meant to be used on arch linux.

## Features

- Application Style : [kvantum-dark](https://github.com/catppuccin/Kvantum/tree/main/themes/catppuccin-latte-sapphire)
- Colors : [Catppuccin Mocha Sapphire](https://store.kde.org/p/1921998)
- Cursors : [Layan-white-cursors](https://aur.archlinux.org/packages/layan-cursor-theme-git)
- Discord theme : [catppuccin-frappe-sapphire](https://github.com/catppuccin/discord)
- Display manager : [sddm](https://archlinux.org/packages/extra/x86_64/sddm/)
- File manager : [Nautilus](https://archlinux.org/packages/extra/x86_64/nautilus/)
- Icons : [papirus-folders-catppuccin](https://aur.archlinux.org/packages/papirus-folders-catppuccin-git)
- Nerd Font : [ttf-meslo-nerd-font-powerlevel10k](https://aur.archlinux.org/packages/ttf-meslo-nerd-font-powerlevel10k)
- Plasma Style : [Utterly-Round](https://store.kde.org/p/1901768)
- Shell : [zsh](https://www.zsh.org/)
- Shell Framework : [ohmyzsh](zsh-theme-powerlevel10k)
- Shell Theme : [powerlevel10k](https://aur.archlinux.org/packages/zsh-theme-powerlevel10k)
- Splash Screen : [Catppuccin Mocha Sapphire](https://github.com/catppuccin/sddm)
- Terminal : [ghostty](https://archlinux.org/packages/extra/x86_64/ghostty/)
- Window Decorations : [CatppuccinMocha-Modern](https://github.com/catppuccin/kde)

## Installation

### Git

```bash
cd ~
git init
git remote add origin https://github.com/leobruant/dotfiles
git fetch --all
git reset --hard origin/kde
## Optional
# Get oh-my-zsh + zsh-syntax-highlighting
git submodule update --init --recursive
# Get powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

### Folders

To get the folders color, run this command

```bash
papirus-folders -C cat-mocha-sapphire
```

### ZSH

To set ZSH as your default shell, run the following command (Log out / log in to see the effects)

```bash
chsh -s /usr/bin/zsh
```

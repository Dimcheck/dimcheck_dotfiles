# dimcheck_dotfiles

## Deps
- Install [stow](https://www.gnu.org/software/stow/) according to your system distribution
- Install [ml4w-hyprland-starter](https://github.com/mylinuxforwork/hyprland-starter)
- Install [extra/wofi](https://archlinux.org/packages/extra/x86_64/wofi/)
- Install [hyprshot](https://aur.archlinux.org/packages/hyprshot)
- Install [nautilus](https://archlinux.org/packages/extra/x86_64/nautilus/)
- Install [swaync](https://archlinux.org/packages/extra/x86_64/swaync/)
- Install [FiraMonoNerdFont](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/FiraMono.zip) and unzip it content to /usr/local/share/fonts/otf

## Setup
- Clone the repo and cd into it.
- Make sure that there is no directories in .config with same names. Stow will create symlink instead of regular directory.
- To apply alacritty(you can substitude "alacritty" to another program name) config use this command:
 ```
 stow -v -t $HOME alacritty
 ```

## Uninstall
- To disable symlinks from alacritty config again:
 ```
 stow -v -t $HOME -D alacritty
 ```

## Result
Enjoy the final look✨:
![final-look](./example/final-look.jpg)

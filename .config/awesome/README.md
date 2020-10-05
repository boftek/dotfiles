## Awesome WM config

I pulled a git repository from the user [Chris Titus](https://github.com/ChrisTitusTech/material-awesome) and slighltly modified it to my needs.

What I did: \
  * Removed time and date from top panel \
  * Removed taskbar from left panel \
  * Changed Brave logo to Firefox logo \
  * Added a desktop for terminal (launches urxvt) \
  * Changed logo from light to bold \
  * Changed the default wallpaper \
  * Music desktop now launches spotify 
  
Feel free to clone this repo and use it on your own system.

If you want to customize it yourself this may help you:
* [Configuration](./configuration) is about all the **settings** available
* [Layout](./layout) hold the **disposition** of all the widgets
* [Module](./module) contain all the **features** available
* [Theme](./theme) hold all the **aesthetic** aspects
* [Widget](./widget) contain all the **widgets** available


## Installation

### 1. Get the dependencies

#### Debian-Based

```
sudo add-apt-repository ppa:regolith-linux/unstable -y
sudo apt install awesome fonts-roboto rofi picom i3lock xclip qt5-style-plugins materia-gtk-theme lxappearance xbacklight kde-spectacle nautilus xfce4-power-manager pnmixer network-manager-applet gnome-polkit -y
wget -qO- https://git.io/papirus-icon-theme-install | sh
```

#### Arch-Based

```
yay -S awesome rofi picom i3lock-fancy xclip ttf-roboto gnome-polkit materia-gtk-theme lxappearance flameshot pnmixer network-manager-applet xfce4-power-manager -y
wget -qO- https://git.io/papirus-icon-theme-install | sh
```

### Clone and install

```
git clone https://github.com/philippanic/dotz.git
```

Go in this folder then and then in .config

Move the folder awesome in to ~/.config


### External links

[Original README.md](https://github.com/ChrisTitusTech/material-awesome/blob/master/README.md)

# T4MG

T4MG is a GTK-theme for the Manjaro gnome desktop, fork of https://github.com/paullinuxthemer/T4G

T4MG (Theme For Manjaro Gnome)

<a href="https://imgur.com/TZcvP7a"><img src="https://i.imgur.com/TZcvP7a.png" title="source: imgur.com" /></a>

A heavily modified version of the Arc-theme with many transparent items

This is a pure gnome edition: Only GTK 3 and GTK 2 files included 
Works with 3.20+, 3.28

To put the buttons to the left open a terminal:

gsettings set org.gnome.desktop.wm.preferences button-layout "close,minimize,maximize:"

### GTK2 ENGINES REQUIREMENT

- GTK2 engine Murrine
- GTK2 engine Pixbuf

Fedora/RedHat distros:
> `yum install gtk-murrine-engine gtk2-engines`<br/>

Ubuntu/Mint/Debian distros:
> `sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf`<br/>

Arch Linux/Manjaro Linux:

> `sudo pacman -S gtk-engine-murrine gtk-engines`<br/>

### how to install:

Extract and put it into the themes directory i.e. ~/.themes/ or /usr/share/themes/ (create it if necessary).Then change the theme via distribution specific tool like Gnome tweak tool or Unity tweak tool, etc. (If you use Snap-packages instead of app's from the normal repositories than definitely put the theme to /usr/share/themes

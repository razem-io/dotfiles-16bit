# dotfiles-16bit
My custom dotfiles configuration with a lot of inspiration from the awesome [base16 theme](https://github.com/chriskempson/base16).

![Screenshot](https://raw.githubusercontent.com/razem-io/dotfiles-16bit/master/screenshot.png)

##Dependencies
To use this theme there isn't anything required besides awesome wm and font awesome.
However I added several custom shortcuts and autostart commands which 
require applications to be installed.

I use arch and make use of AUR repositories. Sadly I do not have the time to support other distros.

With yaourt simply execute the following to install everything which might be missing:

###Required
`yaourt -S --needed git awesome-git awesome-themes-git ttf-font-awesome vicious lua-dkjson fish rxvt-unicode ttf-dejavu`
###Optional
`yaourt -S --needed compton network-manager-applet dunst pulseaudio pasystray rofi imagemagick feh`

##Wallpaper
Sadly I can not find the license for the wallpaper. That is why it is not included in the repository. 
You can however find it [here](http://imgur.com/FI5cosR).

##GTK Theme
I use [ceti2](https://github.com/horst3180/arc-theme) by [horst3180](https://github.com/horst3180/) (ceti-2-themes-git)
`yaourt -S --needed arc-themes`

##Chrome/Firefox Theme
I use the theme provided by arc.

##Icon Theme
Paper-Icons `paper-icon-theme-git`


# Dracula Polybar Themes
Polybar themes with dracula color scheme and style

## Note :
This Polybar setup is a modified version from one of Polybar Themes collection by 
[@adi1090x](https://github.com/adi1090x/polybar-themes#-polybar-12) .

## Requirements :
* [polybar](https://github.com/polybar/polybar) installed.
* Fonts : [Material Icons](https://github.com/aufarijaal/dracula-polybar/tree/master/fonts), [Iosevka Nerd Font](https://github.com/aufarijaal/dracula-polybar/tree/master/fonts), [waffle](https://github.com/aufarijaal/dracula-polybar/tree/master/fonts) , [Hind Siliguri](https://github.com/aufarijaal/dracula-polybar/tree/master/fonts), [Font Awesome](https://github.com/aufarijaal/dracula-polybar/tree/master/fonts/font-awesome)
* For Openweather modules : $CITY , $KEY. go [here](https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/openweathermap-detailed), or [here](https://forum.archlabslinux.com/t/polybar-weather/1357/8) for more information

## How to use
These are just simple config files, to use these themes, clone this *repo* and copy all the config files to *$HOME/.config/polybar*
+ Make sure you've installed the required fonts or you'll face *Dropping character* issue.
+ Don't change the path of scripts or they won't work.

Setps..
```bash
# change to home dir
cd $HOME

# clone this repo
git clone https://github.com/aufarijaal/dracula-polybar.git

# go to the dracula-polybar directory
cd dracula-polybar

# copy fonts to local fonts dir (i'll put the fonts in all dirs)
cp -r fonts/* ~/.local/share/fonts

# reload font cache
fc-cache -v

# copy everything from polybar-1 to polybar config dir (backup your config first if you have)
cp -r * ~/.config/polybar

# run
polybar -r main -c ~/.config/polybar/config.ini &
```
## Preview

![bar](https://github.com/aufarijaal/dracula-polybar/blob/master/assets/screenshot2.png)
<br>
![scrot](https://github.com/aufarijaal/dracula-polybar/blob/master/assets/screenshot1.png)

## Thanks
Thanks to [adi1090x](https://github.com/adi1090x) for the theme.
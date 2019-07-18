# dotfiles
backup of personal configuration files

TODO: To add config files for the following
* vimrc
* ~~i3~~
* mpv
* bashrc


## Dependencies

### For i3-gaps

Following command line tools must be installed for the i3 configuration to work-

Media control keys
* pactl - Audio control
* xbacklight - Screen brightness control
* playerctl - Media playback control
* i3lock - Lock screen

Two seperate scripts-
* [kb-light.py](https://wiki.archlinux.org/index.php/Keyboard_backlight) - Keyboard brightness control
* toggletouchpad.sh - Enable/disable touchpad

Run on startup-
* synclient - For configuring natural scrolling
* fehbg - For setting up the wallpaper
* compton - Start compositor
* nm-applet - Show network manager in i3status

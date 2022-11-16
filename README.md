# sway-window

This is a rofi-script to select windows in swaywm. The default window selector of rofi does not play well enough with sway for me.

## Install

`sudo cp sway-window /usr/local/bin/`

## Usage

`rofi -modi "swaywindow:sway-window" -show swaywindow -i -show-icons`

### Example for sway config

`bindsym Alt+Tab exec "rofi -modi "swaywindow:sway-window" -show swaywindow -i -show-icons"`

## Dependencies

- swaywm
- python>3.6
- [rofi-wayland](https://github.com/lbonn/rofi)

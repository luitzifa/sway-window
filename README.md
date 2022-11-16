# sway-window

The default window selecter of rofi does not play well enough with sway.

## Install

`sudo cp sway-window /usr/local/bin/`

## Usage

`rofi -modi "swaywindow:sway-window" -show swaywindow -i -show-icons`

### Example for sway config

`bindsym Alt+Tab exec "rofi -modi "swaywindow:sway-window" -show swaywindow -i -show-icons"`

## Dependencies

- swaywm
- python>3.5
- [rofi-wayland](https://github.com/lbonn/rofi)

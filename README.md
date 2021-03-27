# Gitmofi

Gitmofi is a script for rofi, it allows you copy emojis for your commits, following the [Gitmoji](https://gitmoji.dev/).

## Install

* Clone the respository `git clone https://github.com/sergius02/gitmofi.git`
* Execute the script `./install`

## Usage: 
* Bind `rofi -modi "gitmofi:gitmofi" -show gitmofi` to a key combination.

For example, for **i3wm** add this to your `$HOME/.config/i3/config`

`bindsym $mod+g exec --no-startup-id rofi -modi "gitmofi:gitmofi" -show gitmofi`

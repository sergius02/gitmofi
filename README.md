# ✨ Gitmofi ✨

Gitmofi is a script for rofi, it allows you copy emojis for your commits, following the [Gitmoji](https://gitmoji.dev/) guide.

## 🚀 Install

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/sergius02/gitmofi/main/install)"`

## ⚡️ Usage: 
* Bind `rofi -modi "gitmofi:gitmofi" -show gitmofi` to a key combination.

For example, for **i3wm** add this to your config

`bindsym $mod+g exec --no-startup-id rofi -modi "gitmofi:gitmofi" -show gitmofi`

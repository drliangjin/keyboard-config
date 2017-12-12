# Karabiner-Elements Config

## Complex Modifications
### Modifier Keys
- Map Caps Lock to Left Control, or Escape if pressed alone
- Map Return/Enter to Right Control, or Return/Enter if pressed alone
- Map Left Shift to Left Shift, or Opening Parenthesis if pressed alone
- Map Right Shift to Right Shift, or Closing Parenthesis if pressed alone
### Others
## Installation
- Karabiner-Elements via homebrew
```
brew cask install karabiner-elements
```
## Configuration
- Personal configuration via git
```
git clone https://github.com/drliangjin/karabiner.json ~/.config/karabiner/
```
## ToDo
- Map left alt to left alt, or something useful if pressed alone
- Map right alt to right alt, or something useful if pressed alone
## Enjoy!

# Linux (without Karabiner-Elements)
## Arch/Manjaro with Gnome DE
- Create a .desktop file under ~/.config/autostart/
- Create executable shell script under dotfile directory
- NOTE for desktopfile command:
```
sh -c '~/ScriptName
```

## Resources
- a comprehensive [guide](https://medium.com/@damko/a-simple-humble-but-comprehensive-guide-to-xkb-for-linux-6f1ad5e13450)
- a [guide](https://www.linux.com/learn/hacking-your-linux-keyboard-xkb) for pressing both shift keys as caps lock

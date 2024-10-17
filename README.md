### Project Archived

> [!NOTE]
> I haven't used Arch, i3, or anything related to this project for several years now. As such, I've archived this repo. If you'd like to contribute to this project please support one of the forks, or create your own! ❤

---

# Menu Surfraw

A short little Bash script that uses rofi or dmenu to prompt you for an Elvis and a search term with surfraw.

## Installation

This'll work anywhere. You could place it in `~/.local/bin` or `/usr/bin` and have it built into dmenu, I use it in i3 with this line in my configuration: `bindsym $mod+Mod1+space exec ~/.dotfiles/menu-surfraw`, it's up to you!

## Preview

![Menu Surfraw Preview](https://raw.githubusercontent.com/TomboFry/menu-surfraw/master/preview.gif)

## Usage

```
menu-surfraw [OPTIONS] [ELVIS [SEARCHTERM]]

OPTIONS:
  -h, --help	Displays this message

ELVIS:
    This is the same as surfraw, any Elvis you have installed. Can be left
    blank, as you will be prompted for this in dmenu/rofi.

SEARCHTERM:
    Again, the same as surfraw, the term you are searching for. Can also be
    left blank as you will be prompted for this in dmenu/rofi.
```
## Dependencies

- Dmenu
- Surfraw
- Rofi (optional)

## License

Do what you like, this script makes use of Unlicense so it's essentially public domain!

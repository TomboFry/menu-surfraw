# Menu Surfraw

A short little Bash script that uses rofi or dmenu to prompt you for an Elvis and a search term with surfraw.

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

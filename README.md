# alacritty-hackthebox-theme

![htb-theme](https://i.imgur.com/7fOTZ2U.png)

## Install
1. Download the `htb.yml` file;
2. Import `htb.yml` in `~/.config/alacritty/alacritty.yml`:

```yml
import:
  - /path/to/htb.yml
```

Alternatively, use the schemes feature to create a new scheme and set the newly created scheme as the current theme:
```yml
htb: &htb
    primary:
      background: '#141d2b'
      foreground: '0xa4b1cd'

  # Normal colors
    normal:
      black:   '0x2e2e2e'
      red:     '0xff8484'
      green:   '0xc5f467'
      yellow:  '0xffcc5c'
      blue:    '0x5cb2ff'
      magenta: '0xcf8dfb'
      cyan:    '0x5cecc6'
      white:   '0xc5d1eb'

    # Bright colors
    bright:
      black:   '0x565656'
      red:     '0xec5357'
      green:   '0xc0e17d'
      yellow:  '0xf9da6a'
      blue:    '0x49a4f8'
      magenta: '0xa47de9'
      cyan:    '0x99faf2'
      white:   '0xffffff'

colors: *htb
```

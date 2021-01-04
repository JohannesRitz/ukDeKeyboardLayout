# Type German on English Keyboard (Ubuntu/Debian/Linux)

Having an UK keyboard but wanting to write in German demands a solution.
This one is a modified `/usr/share/X11/xkb/symbols/gb`

## Setup
 * `git clone https://github.com/JohannesRitz/ukDeKeyboardLayout.git`
 * `sudo cp ukDeKeyboardLayout/gb /usr/share/X11/xkb/symbols/gb`
 * Settings > Langugage > select British English keyboard layout
 * `reboot`

## Usage
```
| Type                     | Get |
|`<alt gr> + <a>`          | ä |
|`<alt gr> + <shift> + <a>`| Ä |
|`<alt gr> + <o>`          | ö |
|`<alt gr> + <shift> + <o>`| Ö |
|`<alt gr> + <u>`          | ü |
|`<alt gr> + <shift> + <u>`| Ü |
|`<alt gr> + <s>`          | ß |
|`<alt gr> + <shift> + <s>`| ẞ |
```

## See also
Using [xmodmap](https://medium.com/@retprogramisto/how-to-make-custom-keyboard-map-with-xmodmap-1341a1552d4f) instead.

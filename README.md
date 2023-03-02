## Dependencies
```terminal
sudo apt install scrot zbar-tools xclip
```

## Install
```terminal
wget https://raw.githubusercontent.com/pablos123/extremely_complex_qr_scanner/main/qr_screen_scanner -P $HOME/.local/bin/ && chmod +x $HOME/.local/bin/qr_screen_scanner
```
This will create a file in `$HOME/.local/bin/` named `qr_screen_scanner`

If `qr_screen_scanner` is not available after you run the command above you don't have `$HOME/.local/bin/` in your `$PATH`.

Maybe that's because you didn't have the directory before running the command. In general `.profile` will load that directory if exists as part of your `$PATH`, so the next time you login or `source` `.profile` you'll have `qr_screen_scanner` available.

Execute `qr_screen_scanner` to read a qr code in the screen.

This supports multiple qr in the screen if they are valid qr's.

## Try it out!

![darksous](https://user-images.githubusercontent.com/52180403/222567947-05b7496b-9b5c-4221-b308-020dd6e68b64.png | =250x250)
![bull](https://user-images.githubusercontent.com/52180403/222568140-2d2ba09c-5333-49aa-9df2-6796d08a65d8.png | =250x250)

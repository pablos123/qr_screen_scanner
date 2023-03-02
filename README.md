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

Execute `qr_screen_scanner` to read a qr code (or more than one!) in the screen.

## Try it out!

<img src="https://user-images.githubusercontent.com/52180403/222569613-e3230131-0ae5-4865-bc64-f4ae2415f2ca.png" width="100" height="100">
<img src="https://user-images.githubusercontent.com/52180403/222570023-52583da7-c82b-4246-9c76-67d315f1ba9e.png" width="100" height="100">

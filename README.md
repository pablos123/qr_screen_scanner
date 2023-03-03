## Dependencies
```terminal
sudo apt install scrot zbar-tools xclip
```

## Install
```terminal
mkdir -p $HOME/.local/bin/ && rm -f $HOME/.local/bin/qr_screen_scanner && wget https://raw.githubusercontent.com/pablos123/extremely_complex_qr_scanner/main/qr_screen_scanner -P $HOME/.local/bin/ && chmod +x $HOME/.local/bin/qr_screen_scanner
```
This will create a file in `$HOME/.local/bin/` named `qr_screen_scanner`

If `qr_screen_scanner` is not available after you run the command above you don't have `$HOME/.local/bin/` in your `$PATH`.

Maybe that's because you didn't have the directory before running the command. In general `.profile` will load that directory if exists as part of your `$PATH`, so the next time you login or `source` `.profile` you'll have `qr_screen_scanner` available.

Execute `qr_screen_scanner` to read a qr code (or more than one!) in the screen.

## Try it out!

<img src="https://user-images.githubusercontent.com/52180403/222609479-88fad340-a000-4247-80cd-7954627f292c.png" width="100" height="100">
<img src="https://user-images.githubusercontent.com/52180403/222609473-5546cbc6-b85f-4ba9-a635-2b1d85cf1e62.png" width="100" height="100">

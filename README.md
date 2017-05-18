# Overview

Plays Lil Jon sound clips. If you have figlet and lolcat installed it will pretty-print the clip titles.

I use it to alert me to long-running commands that have finished.

`command; lil_jon`

## Example

```
> lil_jon
(sounds play)
 ____  _   _    _    ____   __   __ _      _____ ___ _   _  ____    _    ____  
/ ___|| \ | |  / \  |  _ \  \ \ / // \    |  ___|_ _| \ | |/ ___|  / \  / ___| 
\___ \|  \| | / _ \ | |_) |  \ V // _ \   | |_   | ||  \| | |  _  / _ \ \___ \ 
 ___) | |\  |/ ___ \|  __/    | |/ ___ \  |  _|  | || |\  | |_| |/ ___ \ ___) |
|____/|_| \_/_/   \_\_|       |_/_/   \_\ |_|   |___|_| \_|\____/_/   \_\____/ 
                                                                               
 ____   _  _____ ____   ___  _   _   _____ _____ ___  _   _ ___ _        _    
|  _ \ / \|_   _|  _ \ / _ \| \ | | |_   _| ____/ _ \| | | |_ _| |      / \   
| |_) / _ \ | | | |_) | | | |  \| |   | | |  _|| | | | | | || || |     / _ \  
|  __/ ___ \| | |  _ <| |_| | |\  |   | | | |__| |_| | |_| || || |___ / ___ \ 
|_| /_/   \_\_| |_| \_\\___/|_| \_|   |_| |_____\__\_\\___/|___|_____/_/   \_\
                                                                              
>
```

## Encoding

`ffmpeg -i input.wav -c:a libfdk_aac -vbr 4 output.m4a`

## Future Plans

- mix a unique track on each run with samples from http://beatproduction.net/sound-kits/lil-jon-crunk-sound-kit/

## Credits

sounds are from https://github.com/GabeJacobs/Lil-Jon-App/tree/master/sounds

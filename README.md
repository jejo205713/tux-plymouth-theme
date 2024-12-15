# tux-plymouth-theme
a linux tux boot screen (plymouth theme)

![Boot Screen](https://github.com/jejo205713/tux-plymouth-theme/raw/main/mac/boot.png)


## Installation

1. Clone this repo and then `cd` to it.

         git clone https://github.com/jejo205713/tux-plymouth-theme.git && cd tux-plymouth-theme
        
2. Copy **mac** folder to `/usr/share/plymouth/themes` directory and `cd` to there.

         sudo cp -r mac /usr/share/plymouth/themes && cd /usr/share/plymouth/themes

3. Run the command below.
        
         sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/mac/mac.plymouth 100
        
4. And then run:
        
         sudo update-alternatives --config default.plymouth
        
   to choose and set the default theme.

5. Finally, run:
        
         sudo update-initramfs -u

## CREDITS : 
JEJO.J

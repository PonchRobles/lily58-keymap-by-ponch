# Lily58 Keymap by PonchRobles
This repository contains the custom keymap for a lily 58 keyboard.
The steps of colleague [JC Nerd](https://www.youtube.com/c/JCNerd/featured) were followed, where he explains the step by step of the construction of the custom keymap, the files were adapted to adapt to the lily58.
_________
Este repositorio contiene el mapa de teclas personalizado para un teclado lily58.
Se siguieron los pasos del colega [JC Nerd](https://www.youtube.com/c/JCNerd/featured), donde explica el paso a paso de la construccion del keymap personalizado, se fue adecuando los archivos para adaptarse a el lily58.
## Usage
| :warning: WARNING          |
|:---------------------------|
| To be able to follow these steps it is necessary to have the qmk_toolbox development environment installed, if not, I recommend this guide [qmk_tolbox](https://youtu.be/mz8WG5e--jA?t=248).      |

Clone this repo in your folder lily58. (This folder tends to be at Computer > Local Disk (C :) > Users > YOUR_USER_NAME > qmk_firmware > keyboards > lily58)

To compile the files and generate the .hex file, you must follow these steps in the MSYS2 MinGW 64-bit terminal:
 - cd $USERPROFILE/qmk_firmware (Windows)
 - qmk compile -kb lily58 -km ponch
 ###### In the previous line the part of "lily58" is the name of the folder where our keymap is located, the part of "ponch" is the name of the folder of our keymap.
 If everything was correct, the .hex file must be found in the path: C: \ Users \ YOUR_USER_NAME \ qmk_firmware, and its name must be      "ContainerFolderName_rev1_KeymapFolderName.hex"
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GNU](http://www.gnu.org/licenses/)

## The original keymap
This is the c configuration file for the keymap

Copyright 2012 Jun Wako <wakojun@gmail.com>
Copyright 2015 Jack Humbert

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

These files were modified by [PonchRobles](https://github.com/PonchRobles/) 2020.

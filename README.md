# xyztkl rev2

[<img src="img/KOK_0241.jpg" width="800px">](https://raw.githubusercontent.com/xyzz/xyztkl-r2/master/img/KOK_0241.jpg)
[<img src="img/KOK_0197.jpg" width="800px">](https://raw.githubusercontent.com/xyzz/xyztkl-r2/master/img/KOK_0197.jpg)
[<img src="img/KOK_0249-2.jpg" width="800px">](https://raw.githubusercontent.com/xyzz/xyztkl-r2/master/img/KOK_0249-2.jpg)

*— Photos by [@kokaloo_](https://www.instagram.com/kokaloo_/)*

## License

CC0 apart from the switch footprints and component STEP models, see LICENSE.txt.

## Known issues

- The PCB is a bit hard to align inside the case
- The screw holes aren't at the same depth from the top

## Notes

- dboard: this uses a custom daughterboard; should be 1mm thick. JST cable or pinout **not** compatible with ai03 daughterboard
- pcb: the included PCB is using STM32F103 (or a compatible clone), you will need an ST-LINK to program the included bootloader; recommend matching the color to the color of the bottom piece if possible; should be 1.6mm thick
- jst cable: 100mm, reverse orientation (pins 1-4 on one side map to 4-1 on the other) - note that this is the opposite of what ai03 unified daughterboard uses, if you use a wrong cable you risk killing the pcb
- ALPS support: an alps-compatible PCB and plate files are provided, however they are designed to be used with the Tai Hao alps keyset and an MX spacebar; no compatibility for other layouts is provided

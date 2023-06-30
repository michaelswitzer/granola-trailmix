# TrailMix by Granola Arcade
The TrailMix is a button box style arcade controller by Granola Arcade. It is designed to provide the minimum cost professional grade arcade stick available. The design of the TrailMix is simplified down to the core, without any of the bells and whistles that add cost and complexity. Win your local without breaking the bank!

You can buy the TrailMix at https://granola.games

## Build your own
First, you should decide if building your own TrailMix is the right choice for you. It will definitely be more expensive than buying one directly from Granola Arcade, and it isn't as fun to put together as some of the other DIY options. Nevertheless, if you decide to press on, the files in this repository should have everything you need.

The TrailMix is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. In simple terms, this means you are welcome to use or remix these designs to build your own TrailMix free of cost. You are *not* permitted to sell the TrailMix commercially. You also can't republish the designs without attribution and without carrying this license forward into your new designs. For more information see the license file in this repository.

To build your own TrailMix, import the PCB designs and bill of materials using KiCAD. We provided a list of parts that use JLCPCB's part assembly services, since that is the company we use to manufacture the PCB. You can use these files as a starting point for building your own PCB.

The STL file for the case is optimized for FDM 3D printers. We recommend PLA but you can use any material you wish. The case is designed to be printed on the thin edge on the top side, which can cause some stability challenges when printing. **This orientation is better suited to printers that do not move their print bed side to side, and can be tricky to print on Prusa/Ender/etc. printers.** If you use a "bed slinger" printer such as these, make sure you have good bed adhesion.

You will also need to source your own key switches and keycaps. The TrailMix uses Kailh low-profile "Choc v1" keyboard switches.

## Firmware
The TrailMix is designed to use the <a rel="GP2040-CE firmware" href="https://github.com/OpenStickCommunity/GP2040-CE">GP2040-CE firmware</a>. You want the .uf2 file for the Raspberry Pi Pico as it has the same pinouts as the TrailMix. If you wish to use different firmware, you can view the schematic files to understand the layout of the board. If you bridge the Boot and GND pins (marked "BOOT" on the PCB) as you plug in the USB cord, you can upload new firmware in .uf2 format.

## Credits
The TrailMix was designed by Michael Switzer. The GP2040-CE firmware is maintained by <a href="https://github.com/OpenStickCommunity">OpenStickCommunity</a>. This project was inspired by the <a href="https://github.com/jfedor2/flatbox">Flatbox</a>.

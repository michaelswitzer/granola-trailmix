# TrailMix by Granola Arcade

![TrailMix fightstick](/Images/trailmix.jpg "TrailMix fightstick")

The TrailMix is a button box style arcade controller by Granola Arcade. It is designed to provide the minimum cost professional grade arcade stick available. The design of the TrailMix is simplified down to the core, without any of the bells and whistles that add cost and complexity. Win your local without breaking the bank!

You can no longer buy the TrailMix from Granola but you can buy our current controllers at https://granola.games

## Should you make a TrailMix?
Building your own TrailMix will definitely be more expensive than buying one directly from Granola Arcade, and it isn't as fun to put together as some of the other DIY options out there. Nevertheless, if you decide to press on, the files in this repository should have everything you need.

## How to build
To build your own TrailMix, import the PCB designs and bill of materials using KiCAD. I provided a list of parts that use JLCPCB's part assembly services, since that is the company I use to manufacture the PCB. You can use these files as a starting point for building your own PCB.

The STL file for the case is optimized for FDM 3D printers. I recommend PLA with at least 15% infill but you can use any material you wish. The case is designed to be printed on the thin edge on the top side, which can cause some stability challenges when printing. **This orientation is better suited to printers that do not move their print bed side to side, and can be tricky to print on Prusa/Ender/etc. printers.** If you use a "bed slinger" printer such as these, make sure you have good bed adhesion.

You will also need to source your own key switches and keycaps. The TrailMix uses Kailh low-profile "Choc v1" keyboard switches.

## Firmware
The TrailMix is designed to use the <a rel="GP2040-CE firmware" href="https://github.com/OpenStickCommunity/GP2040-CE">GP2040-CE firmware</a>. You want the .uf2 file for the Raspberry Pi Pico as it has the same pinouts as the TrailMix. If you wish to use different firmware, you can view the schematic files to understand the layout of the board. If you bridge the Boot and GND pins (marked "BOOT" on the PCB) as you plug in the USB cord, you can upload new firmware in .uf2 format.

## Credits
The TrailMix was designed by Michael Switzer. The GP2040-CE firmware is maintained by <a href="https://github.com/OpenStickCommunity">OpenStickCommunity</a>. This project was inspired by the <a href="https://github.com/jfedor2/flatbox">Flatbox</a>.

# TrailMix by Granola Arcade
The TrailMix is a button box style arcade controller by Granola Arcade. It is designed to provide the minimum cost professional grade arcade stick available-- The design of the stick is simplified down to the core, without any of the bells and whistles that add cost and complexity. Win your local without breaking the bank!

You can buy the TrailMix at https://granola.games

## Build your own
The TrailMix is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. In simple terms, this means you are welcome to use or remix these designs to build your own TrailMix free of cost. You are *not* permitted to sell the TrailMix commercially, or republish the designs without attribution and carrying this license forward into the new design. For more information see the license file in this repository.

To build your own TrailMix, import the PCB designs and bill of materials using KiCAD. We provided a list of parts that use JLCPCB's part assembly services, since that is the company we use to manufacture the PCB. You can use these files as a starting point for building your own PCB.

The STL file for the case is optimized for FDM 3D printers. We recommend PLA but you can use any material you wish.

You will also need to source your own key switches and keycaps. The TrailMix uses Kailh low-profile "Choc v1" keyboard switches.

## Firmware
The TrailMix is designed to use the <a rel="GP2040-CE firmware" href="https://github.com/OpenStickCommunity/GP2040-CE">GP2040-CE firmware</a>. If you wish to use different firmware, you can view the schematic files to understand the pinouts. If you bridge the Boot and GND pins (marked "J1" on the PCB) as you plug in the USB cord, you can upload new firmware in .uf2 format.

## Credits
The TrailMix was designed by Michael Switzer. The GP2040-CE firmware is maintained by <a href="https://github.com/OpenStickCommunity">OpenStickCommunity</a>. This project was inspired by the <a href="https://github.com/jfedor2/flatbox">Flatbox</a>.

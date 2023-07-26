# Build Guide

Actual build guide is underway, but it's very similar to [choc version](/build-guide/choc/readme.md).

## Gerber files

- [PCB](/gerbers/mx/pcb.zip)

## Case files (3d printed)

All files are in [stl](/stl/mx) folder.

- 5mm plate for MX switches
- 2.5mm plate for KS-27/KS-33 switches
- different plate version for rotary and roller encoders. The only difference is encoder hole's size, if you're not sure, grab one with roller.
- covers
  ![](/images/mx-covers.jpg)

## Materials

- PCBs
- Case (6 parts)
- 2 Waveshare [RP2040 Zero](https://www.aliexpress.com/item/3256804090654134.html) MCUs
- 38 [SMD SOD-123 1N4148](https://www.aliexpress.com/item/1005002882901030.html) diodes
- 2 [EC11/12 rotary encoder](https://www.aliexpress.com/item/33006686909.html) with [knob](https://www.aliexpress.com/item/1005003425428192.html) or [Panasonic EVQWGD001 roller encoder](https://www.aliexpress.com/item/32990950196.html)
- 5mm (and 6mm if normal case) M2 [screws with flat head](https://www.aliexpress.com/item/4001248931159.html)
- M2 [nuts](https://www.aliexpress.com/item/1005001412230125.html)
- [LCD 1.69" 240x280 display](https://www.aliexpress.com/item/1005004922900927.html)
- Right angled PH2.0 8pin [male connector](https://www.aliexpress.com/item/1005003115054198.html)
- PH2.0 8 pin [female connector with wires](https://www.aliexpress.com/item/4000130210271.html)
- 40mm flat/curved Cirque trackpad (I2C or SPI)
- Vertical 12pin FFC/FPC [connector](https://www.aliexpress.com/item/10000000737049.html)
- Horizontal 12pin FFC/FPC connector - optional
- 12pin 0.5mm pitch 10cm [FFC cable](https://www.aliexpress.com/item/1005002468369055.html) - grab both reverse and forward variants, in case you solder the connector upside down
- TRRS [connectors](https://www.aliexpress.com/item/4000661212458.html) and [cable](https://www.aliexpress.com/item/1005003676559658.html)
- USB-C [16pin connectors](https://www.aliexpress.com/item/1005003670899595.html) and [cable](https://www.aliexpress.com/item/1005004649061153.html) - optional
- [RGB LEDs 3mA](https://www.aliexpress.com/item/1005003636607308.html)
- [7x1.5 legs](https://www.aliexpress.com/item/1005002995402961.html)
- 8mm magnets (if needed) - 2mm height

## Tools

- Soldering iron. Any iron will work, but I highly recommend something small like TS100 or Pinecil with TS-K tip, it's good for SMD soldering
- Solder, preferably with lead if you can get one. For EU I recommend this [shop](https://botland.store) and Cynel brand. 0.56mm is great for SMD, and you can optionally get 0.9mm for hotswap sockets
- [Soldering paste](https://www.aliexpress.com/item/4000602425410.html)
- [Flux](https://www.aliexpress.com/item/1005004441105643.html)
- Tweezers (I prefer [reverse](https://www.aliexpress.com/item/1005004188266714.html) instead of regular), pliers, soldering mat, isopropyl alcohol (IPA) and [cotton pads](https://www.aliexpress.com/item/1005003798227116.html) for cleaning

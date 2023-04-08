# stront

Split keyboard with 38 keys, LCD display and Cirque trackpad.

## Features

- low profile with Choc V1 switches
- wired split with USB-C or TRRS interconnection
- 38 keys
- roller/rotary encoders
- LCD display (1.69" 240x280 by default)
- Cirque trackpad (40mm by default)
- 2-key pinky columns
- splay on ring/pinky columns
- 3D printed cases

**PCB has all SPI/I2C contacts exposed, so any other device can be used instead, it's just a matter of changing the case (at least that's the idea).**

## Photos

![](./images/top.jpg)
![](./images/pcb.jpg)
<video src="https://user-images.githubusercontent.com/910255/230727603-dd550fdb-f6c9-4c04-b770-03d1b5c3b9b1.mp4" height="200" controls />

## Gerber files

- [PCB](./gerbers/choc/pcb.zip)

## Case files (3d printed)

All files are in [stl](stl) folder.

- thin version - just cutouts for all elements, as low as it can be. May be combined with normal top case and metal bottom plate for additional weight. Has additional holes for 8mm magnets.
  ![](./images/bottom.jpg)
- normal (1mm higher)
  ![](./renders/bottom.png)

## Ordering

PCB was created in collaboration with [PCBWay](https://www.pcbway.com), so I've added their logo on the PCB. Feel free to remove it and/or use any other manufacturer, however I had very positive experience with PCBWay and their FR4 and silkscreen are high quality so I can definitely recommend them. And as EU customer I particularly liked their fast shipping options and ability to pay all taxes at once.

If you'd like to support me financially please consider ordering using my [shared project](https://www.pcbway.com/project/shareproject/Stront_low_profile_keyboard_85ec2664.html) or use [referral link](https://pcbway.com/g/3wpLAF) for signing up.

3D printed case can be printed at home or ordered from a manufacturer, I tested it with black/white resin.

## Materials

- PCBs
- Case (4 parts)
- 2 Waveshare [RP2040 Zero](https://www.aliexpress.com/item/3256804090654134.html) MCUs
- 38 [SMD SOD-123 1N4148](https://www.aliexpress.com/item/1005002882901030.html) diodes
- 2 [EC11/12 rotary encoder](https://www.aliexpress.com/item/33006686909.html) with [knob](https://www.aliexpress.com/item/1005003425428192.html) or [Panasonic EVQWGD001 roller encoder](https://www.aliexpress.com/item/32990950196.html)
- 8mm M2 [standoffs](https://www.aliexpress.com/item/4001271908929.html)
- 5mm (and 6mm if normal case) M2 [screws with flat head](https://www.aliexpress.com/item/4001248931159.html)
- M2 [nuts](https://www.aliexpress.com/item/1005001412230125.html)
- [LCD 1.69" 240x280 display](https://www.aliexpress.com/item/1005004922900927.html)
- Right angled PH2.0 8pin [male connector](https://www.aliexpress.com/item/1005003115054198.html)
- PH2.0 8 pin [female connector with wires](https://www.aliexpress.com/item/4000130210271.html)
- 40mm flat Cirque trackpad
- Vertical 12pin FFC/FPC [connector](https://www.aliexpress.com/item/10000000737049.html)
- 12pin 0.5 pitch [FFC cable](https://www.aliexpress.com/item/1005002468369055.html) - grab both reverse and forward variants, in case you solder the connector upside down
- [USB-C 16pin](https://www.aliexpress.com/item/1005003670899595.html) or [TRRS PJ-320A](https://www.aliexpress.com/item/4000661212458.html) connectors
- [USB-C](https://www.aliexpress.com/item/1005004649061153.html) or [TRRS](https://www.aliexpress.com/item/1005003676559658.html) cable
- [RGB LEDs](https://www.aliexpress.com/item/1005003636607308.html)
- Rubber [sheet](https://www.aliexpress.com/item/1005003938672544.html) or [7x1.5 legs](https://www.aliexpress.com/item/1005002995402961.html)
- 8mm magnets (if needed) - 2mm for rubber sheet version, 3mm for regular legs

## Firmware

[Host application](https://github.com/zzeneg/qmk-hid-host) for Raw HID communication

QMK (work in progress)

- [source code](https://github.com/zzeneg/qmk_firmware/tree/feature/stront/keyboards/stront)
- [pre-compiled file](./firmware/qmk/stront_zzeneg.uf2)

## Build log

**TODO**

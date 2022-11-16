![CalEPD Logo](https://raw.githubusercontent.com/martinberlin/CalEPD/master/assets/CalEPD-logo.svg)

**CalEPD is an ESP-IDF C++ component to drive epaper displays with ESP32 / ESP32S2**

This repository is a Platformio skeleton which unique aim is to make configuration using build variables easier.

However there are still a few gotchas to resolve that we will clarify in the [WiKi section](https://github.com/martinberlin/cale-platformio/wiki) in order to have a successful build. This will probably go away after some days of testing and collaborations from our component developers

## Demos available

We will add different demos that can be easily selected changing one line in platformio.ini file:

```
[platformio]
; Examples avail: 7-color | wifi required-> cale-7-color | cale-grayscale
src_dir = cale-grayscale
```

Just change *src_dir* and point it to one of the available examples.

- **7-color** a very simple demo to show how to draw things using GFX in any of the supported 7 color epapers
- **cale-7-color** WiFi download of a bitmap file (4 or 24 bit-depth) that you can generate in [CALE.es](https://cale.es) or in any URL of your choice
- **cale-mono-or-3-color** this example is the same as the last one but supports either monochrome or 3 color epapers (Red/Back or Yellow/Black) actually does not matter what color the BMP has if it's not black it will be converted to the colorful pixel.

This examples are not meant to be a ready Firmware by itself but rather to point you in the right direction to be a base Firmware where you can build something on top.

If you like our effort we would like that you ★ this repository and help us testing it, if you want to add a new epaper model that does not exist, please make a PR to our [cale-idf repository](https://github.com/martinberlin/cale-idf) that is where we do the development part. Also if you want to support our work becoming an sponsor there you have the option and also links to [PCB's that we designed](https://www.tindie.com/stores/fasani/) to drive this displays and read sensors in order to make [epaper-weather-stations](https://github.com/martinberlin/epaper-weather-station).

Thanks a lot for your attention and have a good experience using our base code!

**Fasani Corporation** | Barcelona, 2022

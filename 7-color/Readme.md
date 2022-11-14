### 7 color displays

This example was only to draw some colorful squares in 7 color displays. There are 3 different classes:

- color/gdey073d46.h new model [800*480 Good-Display GDEY073D46](https://www.good-display.com/product/442.html) requires PSRAM in ESP32 (Too big buffer, no DRAM left for building)
  Requires SPI-adapter **DESPI-C73**
- color/wave5i7Color.h Did not require PSRAM, same with 4 inches below
- color/wave4i7Color.h Both sold by Waveshare, they do not require SPI adapter, it's built in. 

Colors of the Waveshare are very dim specially in cold temperatures.
In my opinion the GoodDisplay model is much nicer, albeit a bit more expensive, and requires a new SPI adapter. 
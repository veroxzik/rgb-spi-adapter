# rgb-spi-adapter
 Simple breakout board for the TLC59711 for use with rhythm game controllers.

## Current Release

v1.1 swaps the RGB headers around for compatibility with Yuancon controllers.

## Explanation
Designed for common anode RGBs. Individually wired works just fine too.

- Connectors are JST-XH 4 pin.
- Capacitors are 1uF 0805.
- Resistor is 0805, value per TLC59711 datasheet for your desired current.
- Solder jumper only if you're using 3.3V voltage across the board (LED and logic). Otherwise leave it open for 5V.

Use Adafruit TLC59711 library (get from Arduino library manager). It's plug and play!
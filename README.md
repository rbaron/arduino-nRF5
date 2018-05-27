# Arduino Core for Nordic Semiconductor nRF5 based boards

This is a fork from [sandeepmistry/arduino-nRF5](https://github.com/sandeepmistry/arduino-nRF5). This fork adds support for
the ID115 fitness bracelet board, which packs a nRF51822 IC. For more information, check out [this blog](https://rbaron.net/blog).

## Installing

### From git (for core development)

 1. Follow steps from Board Manager section above
 2. ```cd <SKETCHBOOK>```, where ```<SKETCHBOOK>``` is your Arduino Sketch folder:
  * OS X: ```~/Documents/Arduino```
  * Linux: ```~/Arduino```
  * Windows: ```~/Documents/Arduino```
 3. Create a folder named ```hardware```, if it does not exist, and change directories to it
 4. Clone this repo: ```git clone https://github.com/rbaron/arduino-nRF5.git rbaron/nRF5```
 5. Restart the Arduino IDE

## Credits

This core is based on the [Arduino SAMD Core](https://github.com/arduino/ArduinoCore-samd) and licensed under the same [LGPL License](LICENSE)

The following tools are used:

 * [GCC ARM Embedded](https://launchpad.net/gcc-arm-embedded) as the compiler
 * A [forked](https://github.com/sandeepmistry/openocd-code-nrf5) version of [OpenOCD](http://openocd.org) to flash sketches

#### This repo contains the configuration files for my Ender 3 Pro, with 32-bit mainboard (Creality 4.2.2), and BLTouch.


#### Marlin Version: [2.0.7.2](https://github.com/MarlinFirmware/Marlin/archive/2.0.x.zip)

#### BLTouch Wiring:

Because the 4.2.2 & 4.2.7 boards have dedicated BLTouch headers, the pin 27 board found in the Creality BLTouch kit isn't required.

* The 3-pin (dupont) connector plugs into the dedicated BLTouch header
* The 2-pin (Molex PicoBlade) connector plugs into the Z-axis limit switch header, replacing the original cable and switch.


#### Platformio default_envs:
```
default_envs = STM32F103RET6_creality
```


#### Included firmware.bin

I've now included a pre-compiled firmware.bin, ready to be flashed. A diff of the modified files vs originals can be viewed [HERE](https://github.com/aidenatt/Ender-3-Pro-Marlin/compare/4ac6f9b..e730e75).

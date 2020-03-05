# 3D Printer Settings


In this repository based on the [Marlin firmware for 3D printers](http://marlinfw.org), I have branches for different 3D printers that I have set up.

You should be able to go to a branch and 'clone or download' to get a copy of it.


Ender 3 Pro with BL Touch
--
* `1.1.x-Ender3`: [Marlin 1.1.9](https://github.com/clintonblackmore/Marlin/tree/1.1.x-Ender3)
* `2.0.x-Ender3`: [Marlin 2.0.4](https://github.com/clintonblackmore/Marlin/tree/2.0.x-Ender3) (has more features disabled to fit in memory)

Go here for [instructions and official firmware](https://drive.google.com/drive/folders/0B9b1NbuMK524aGhPQXRLTW9mams?usp=sharing).

[YD3D Printer](http://www.ydcanada.ca/index.php/product-category/yd3d-3d-printer/) / DMSCreate DP5
--
* `1.1.x-YD3D` or `1.1.x-DMS-DP5`: Marlin 1.1.9 [YD3D](https://github.com/clintonblackmore/Marlin/tree/1.1.x-YD3D) / [DMS DP5](https://github.com/clintonblackmore/Marlin/tree/1.1.x-DMS-DP5) (untested)
* `1.1.x-YD3D-ZStopSwitch`: [Marlin 1.1.9](https://github.com/clintonblackmore/Marlin/tree/1.1.x-YD3D-ZStopSwitch) with [Z Stop limit switch](https://www.thingiverse.com/thing:1479176)

In the Arduino software, set the board to `Arduino Mega 2560`.

Folgertech FT-5 (1st Revision)
--
* `1.1.x-FT5`: [Marlin 1.1.9 for stock FT-5 R1](https://github.com/clintonblackmore/Marlin/tree/1.1.x-FT5)
* `1.1.x-FT5-DualZMod`: [Marlin 1.1.9](https://github.com/clintonblackmore/Marlin/tree/1.1.x-FT5-DualZMod) for use with [Dual Z Axis Mod](http://dustincorbin.weebly.com/blog/folger-tech-ft-5-dual-z-stepperendstops-mod)

It was really painful getting a bootloader onto the device; I finally used an [Arduino as an AVR programmer](https://www.arduino.cc/en/tutorial/arduinoISP), following some instructions on the internet (perhaps Youtube). I think I downloaded a set of settings for the Arduino software and set the board to a `Sanguino 1284p` but it's all a blur now. If you send me a note or a pull request with better instructions, I'll update them.
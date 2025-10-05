# XiaoCorne (Bluetooth)

![XiaoCorne](./docs/PXL_20251005_140615346.jpg)

A compact, wireless keyboard inspired by the Corne v4 (foostan/crkbd), rebuilt around a Seeed XIAO BLE.
My goal was to create a wireless keyboard, without any noticable micro controller and to minimize unused space.
For reading the battery level, a fully analog indicator with 4 leds is on the top side of the PCB.

Firmware and ZMK config are here: https://github.com/FabianAster/seedCorneModule

I made the PCB with CircuitMaker, and not with KiCad, so i can only share the link to it: https://workspace.circuitmaker.com/Projects/Details/9C26B9D0-BD64-4451-B20A-DC635F824EC1
Gerber files to order the PCB, are in the repo.

## Some more Images

### PCB bottom and battery

![Comparison](./docs/PXL_20251005_134637014.jpg)

For the case to fit it needs to be a 10345 lipo battery, the charging is handled by the Seeeduino XIAO BLE.
The leds on the top side need to be red, since i used simple 358 op amps for voltage comparison, and they drop some voltage to their output.

### PCB top

![Comparison](./docs/PXL_20251005_134645765.jpg)

### Comparison with original Corne V4 on the left, this one on the right

![Comparison](./docs/PXL_20251005_140834343.jpg)

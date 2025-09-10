# DimLED

A simple led dimmer based on ESP-01 Module powered by esphome firmware.

### Renders ( Mark II.b )

![DimLED Mark IIb](./output/images/render.png)
![PCB](./output/images/pcb.png)

### Operating Power

Max Values:

- Max Voltage: 36VDC
- Max Current: 15A
- Max Power: 400W

> Above specs are contstrained by XY-MOS PWM Trigger Module

Recommended Values:

- less than 10A at 12VDC
- less than 6A at 24VDC

### Components

- XY-MOS PWM Trigger Module: https://robu.in/product/switch-drive-high-power-mosfet-trigger-module/
- Mini MP1584 Module: https://robu.in/product/mini-mp1584-dc-dc-adjustable-buck-module-3a/
- DC005 Connector: https://robu.in/product/dc-jack-005a/
- Push Switches: https://robu.in/product/6x6x5-tactile-push-button-switch/
- Capacitor (1000uF): https://robu.in/product/ers1am102f16ot-aishi-1000uf-10v-%c2%b120-plugind8x16mm-aluminum-electrolytic-capacitors-leaded-rohs/

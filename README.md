# LEDBrickHome

Wi-Fi controller compatible with various Lego Lighting kits, designed to enable integration of lighting into Home Assistant via ESPHome.

## Compatability

LEDBrickHome is compatible with lighting kits that use a JST SUR connector with 5V on pin 1, and switched 0V on pin 2 (plus pins 3 & 4 for RGB connectors).

To maximise available number of channels, RGB outputs are shared with single colour outputs.  In other words, a 16 channel controller can support a total of 16 different outputs of a single colour, but for each RGB output used, three single colour outputs are lost.

## PCB Design

The PCB design is created in KiCAD V7, and is a simple 2-layer PCB of 1.6mm thickness.

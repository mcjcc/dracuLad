# DracuLad Build guide
## What you need
- 2x pcbs
- 2x bottom plate, 2x top plate
- 34-36 Switches, either choc low profile v1 or mx compatible ones
- 2 rotary encoders
- 2x pro micro compatible controllers
- 38x sod123 SMD diodes
- 2x reset switches
- 2x TRRS jacks
- 8x 0.7cm standoffs, 16 m2 screws to mount the case 
- usb cable, trrs cable, rotary encoder knobs, keycaps

## What you optionally need
- 2x extra rotary encoders (for the thumb cluster, each additional rotary encoder decreases the needed switchcount by one)
- 20x ws2812b LEDs (if you want underglow)
- 2x SSD1306 OLEDs (128x64)
- 2x OLED cover
- 6x standoffs with m2 screws for the OLED cover (standoff size depends on whether you use the OLEDs or not and probably also how low profile your pro micro is mounted (bit-c for example is a bit higher profile), with OLEDs 1cm is ok)
- 1x pimoroni trackball (this will only fit for the plateless build or the one with the FR4 plate)

## First step: soldering the Diodes
- the diode mark should be aligned with the mark on the PCB
- Solder the diodes on the bottom of the PCB, the PCBs are reversible, therefore you need to decide for one side in the beginning. 
- Put solder on one of the pads, reflow the solder while sliding the diode into place, solder the second side of the diode

## Second step: solder the LEDs
- the little triangle on the LED should allign with the triangle on thr PCB
- do it similar to the diode, first solder one pad, slide in the LED, solder the other 3 joints
- be careful, those things are really heat sensitive 

## Third step
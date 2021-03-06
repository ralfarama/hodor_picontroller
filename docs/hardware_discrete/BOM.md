
# Bill of Materials

| Part Number | Count | Description |
| --- | --- | --- |
| T1 | 1 | AC-DC Dual Output Supply RD-35A or equivalent |
| MCU1 | 1  | Raspberry Pi (any version should work) |
| MCU2 | 1 | Arduino Uno R3 or equivalent |
| U1 | 1 | Sparkfun RFID Reader ID-12LA (WRL-11827) or ID-20LA (WRL-11828) |
| PCB1 | 1 | Sparkfun RFID USB Reader (Sparkfun part number SEN-09963) |
| RLY1 | 1 | Sparkfun Beefcake Relay Control Kit (ver 2.0) (Sparkfun part number KIT-13815) |
| BTN1 | 1 | Large button w/LED (Adafruit Product #1185 or #1190, Sparkfun #COM-09181, or equivalent) |
| BS1, BS2 | 2 | 4-Position Barrier Strip (Clinch Connectors p/n 4-140, Jameco P/N 230990, or equivalent) |
| L1 | 1 | 12V Fail Safe electric strike |
| L2 | 1 | 12V electromagnetic lock |

## Recommended Extra Materials for assembly and testing

* 1 - digital multimeter
* 1 - discrete LED
* 1 - breadboard
* 1 - resistor (recommend 220-1000 ohms)
* 1 - (optional) bench power supply capable of producing 5V and 12V
* 1 - 125KHz RFID card (Sparkfun COM-14325 or equivalent)
* 1 - USB "A" male to "mini-B" male cable for RFID reader

The breadboard, LED and resistor are recommended for testing units as they are
assembled.  The bench power supply is recommended since the Meanwell RD-35A
does not implement short-circuit protection, which can cause problems if power
lines accidentally contact during assembly and test.

## Software

* A terminal monitor program
* Arduino IDE
* A tool for uploading Raspberry Pi images

# ATMEGA328-Motor-Board
The ATMEGA328-Motor-Board is a motor control board using an ATMEGA328 microcontroller and two L298P motor drivers, created with the Open Source EDA design platform [KiCad][1].

## Features

- Control circuitry power supply voltage: 5 - 36 (VDC)
- Motor power supply voltage: 7.5 - 46 (VDC)
- Can control up to 4 DC motors (max 3 Amperes), 2 DC motors (max 6 Amperes), or two stepper motors (max 6 Amperes).
- Can control up to 4 servomotors at 5 VDC using PWM signals.
- Two connectors for incremental dual-channel encoders with configurable 5 or 24 VDC power supply voltage.
- Two connectors for potentiometers or analog setpoint signals 0 - 5 VDC.
- Can monitor the current consumption of each of the four motor power channels independently.
- Three 5 or 24 VDC opto-isolated digital inputs for general-purpose signals (Enable, Run, Stop).
- Two configurable voltage output digital outputs for general-purpose signals.
- Mini-USB port for serial communication with the board controller.
- Three LED indicators for communication of various driver or control states.

## Images
Top side
![Top side](/images/top_side.png)

Bottom side
![Bottom side](/images/bottom_side.png)

## Bill of Materials
References | Value | Total Units
----------|-------|-----------

## License
This design is Free Software; you can redistribute it and/or modify it under the terms of the "GNU General Public License" as published by the "FSF Free Software Foundation," or (at your option) any later version.

This design is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the "GNU General Public License" for more details.

[1]: http://kicad-pcb.org/

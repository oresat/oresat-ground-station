# Station Power Board

This board controls all of the switching of power to components in the ground station.
It accepts it's commands through an I2C interface on the Station Rock64 computer.

The switching is acomplished through an I2C GPIO device setup as 16 output bits. The
bits control mosfet switches provideing both 5VDC and 12VDC circuits.

The board also has an A/D to monitor the RF Power Amplifiers output power detectors. The
characteristics of this power measurement is detailed in the power amplifier testing
spreadsheet unfer RF-systems.

Finally this board provides a temperature measurement of the system enclosures environment.

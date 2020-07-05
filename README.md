# nrf51_module

Modified NRF51_module firmware - updated for eByte E73 2G4M04S1D nrf51822 module. 

The code can be build with the NRF5 SDK12 by changing the path in Makefile, but for convenience a prebuild hex file is also included. 

TODO: Build dependencies, gnuarmemb version/SDK version & links. Hardware repo.


| NRF51822      | STLINK V2     |
| ------------- |---------------|
| GND           | GND           |
| VDD           | 3.3V          |
| SDO           | SWDIO         |
| SCL           | SWCLK         |




| NRF51822      | VESC/ESC      |
| ------------- |---------------|
| VCC           | VCC (3,3v)    |
| P0.09         | TX            |
| P0.11         | RX            |
| GND           | GND           |



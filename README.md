# Monitoring supply voltage and current consumption and creating firmware for Robotont’s power management system
This repository contains files created for my bachelor's thesis. 
* In `robotont-electronics-mainboard` there is electronic schemes for voltage and current measuring.  


* In `robotont-firmware` there is code for I<sup>2</sup>C slave receiver and converting measurements into right units. Code is in `src/svc/measurements.c` and `src/mcu/i2cif.c`. Both files have `.h` files also.  


* In `robotont-firmware-power-management` repository is the firmware for power management controller ATtiny88. It is in file `robotont-firmware-power-management.ino`.  


* In `robotont_driver` repository is the plugin for ROS2 based modular driver, that fills up BatteryState variables with incoming data. The code is in file `src/plugin_bat_state.cpp`.

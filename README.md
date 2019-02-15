# TM4C123Base

Reference Design for the TM4C123GH6PM for Robotics

This is a MCU board for using the ARM Cortex-M4 TM4C123GH6PM microcontroller in small robotics.

It is the same MCU as the TI TM4C123 Launchpad: http://www.ti.com/tool/EK-TM4C123GXL except all pins are available, and the hibernate circuit works. It also has a CMOS battery enabling the RTC functions, and hibernate and wake-up operations. It can turn on/off an external power supply.

The reason we developed this board is that the TM4C123GXL board does not fit well in small robots, and one can not take advantage of the hibernate circuitry.

![alt text](https://raw.githubusercontent.com/altineller/TM4C123Base/master/images/T100.jpg)

It can be programmed using CCS, gcc-arm, or Energia, and it is thoroughly tested. To program it, you either need a TM4C123GXL board or an external debug probe like XDS110.

Although 402 size smd components are used, it is relatively easy to solder it with hand using a hot air station. The gerbers are produced so any board house can build them.

This board has been extensively tested, and also powers the robotics project at https://github.com/altineller/DuckiePilot

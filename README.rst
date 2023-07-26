.. _zephyr-mon:

Zephyr Mon
######

Overview
********

This project is a port of esp_mon2 https://github.com/codewitch-honey-crisis/esp_mon2 to zephyr rtos

See this article https://www.codeproject.com/Articles/5365397/Porting-EspMon-to-ZephyrOS-on-a-STM32-boards-or-ot

This project requires the PC .NET companion application shipped with that project.

.. _zephyr-mon-requirements:

Requirements
************

Your board must:

#. Have a UART which must be bridged to your PC somehow. By default it uses the ST-Link virtual COM port. You can modify it.
#. Have a screen - ILI9341 recommended, but you can use your own with some modifications
#. Have a board overlay that maps the hardware on your device. Again, you'll have to modify it to do this.

Supported Boards
*************
Nucleo H723ZG
Nucleo F767ZI
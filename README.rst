.. _zephyr-mon:

Zephyr Mon
######

Overview
********

This project is a port of esp_mon2 https://github.com/codewitch-honey-crisis/esp_mon2 to zephyr rtos

This project requires the PC .NET companion application shipped with that project.

.. _zephyr-mon-requirements:

Requirements
************

Your board must:

#. Have a UART which must be bridged to your PC somehow
#. Have a screen - ILI9341 recommended, but you can use your own with some modifications
#. Have a board overlay that maps the hardware on your device

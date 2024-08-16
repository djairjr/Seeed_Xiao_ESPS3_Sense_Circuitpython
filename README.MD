## Circuitpython 9.1.1 and 9.2.0 Alpha Firmwares
Running on Seeed Xiao ESP32 S3 Sense with correct pin names and espcamera support.
Source code: https://github.com/djairjr/circuitpython/tree/main/ports/espressif/boards/seeed_xiao_esp32_s3_sense

There is a problem with filesystem generation, which generates CIRCUITPY as readonly
as mentioned here:

https://github.com/adafruit/circuitpython/issues/9507

and here:
https://github.com/adafruit/circuitpython/issues/9528

and also here:
https://github.com/adafruit/circuitpython/issues/9384

Tested workaround: manually install tinyuf2 bootloader at https://github.com/adafruit/tinyuf2/releases
and copy .uf2 files also generates a unusable readonly CIRCUITPY (not show on windows system).

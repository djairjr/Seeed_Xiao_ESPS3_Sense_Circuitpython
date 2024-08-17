## Circuitpython 9.1.1 and 9.2.0 Alpha Firmwares
Running on Seeed Xiao ESP32 S3 Sense with correct pin names and espcamera support.

Update: correcting camera pinout. Improve name os pins.

Seeed Studio need to fill USB_VID and USB_PID list here: 
https://github.com/espressif/usb-pids

'''
Adafruit CircuitPython 9.1.1 on 2024-08-17; Seeed Xiao ESP32-S3 Sense with ESP32S3

>>> import board
>>> dir (board)
['__class__', '__name__', 'A0', 'A1', 'A2', 'A3', 'A4', 'A5', 'CAM_D0', 'CAM_D1', 'CAM_D2', 'CAM_D3', 'CAM_D4', 'CAM_D5', 'CAM_D6', 'CAM_D7', 'CAM_HREF', 'CAM_PCLK', 'CAM_SCL', 'CAM_SDA', 'CAM_VSYNC', 'CAM_XCLK', 'D0', 'D1', 'D10', 'D2', 'D3', 'D4', 'D5', 'D6', 'D7', 'D8', 'D9', 'I2C', 'LED', 'MIC_CLK', 'MIC_DATA', 'MISO', 'MOSI', 'MTCK', 'MTDI', 'MTDO', 'MTMS', 'RX', 'SCK', 'SCL', 'SDA', 'SDCS', 'SPI', 'TX', 'UART', '__dict__', 'board_id']
'''

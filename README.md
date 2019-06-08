# ECC608-Simple-Connection-Test

This communicates ATECC608 secure chip from ESP32 and get infos (serial number, revision number, and current config data),
it helps to make sure the connection between them.

# Requirements

  Platformio with VS Code environment.
  install "Espressif 32" platform definition on Platformio

# Environment reference
  
  Espressif ESP32-DevkitC
  this project initialize both of I2C 0,1 port, and the device on I2C port 0 is absent.
  pin assined as below:


      I2C 0 SDA GPIO_NUM_18
      I2C 0 SCL GPIO_NUM_19

      I2C 1 SDA GPIO_NUM_21
      I2C 1 SCL GPIO_NUM_22
          
  Microchip ATECC608(on I2C port 1)

# Usage

you need to change a serial port number which actually connected to ESP32 in platformio.ini.

# Run this project

just execute "Upload" on Platformio. 

# License

This software is released under the MIT License, see LICENSE.

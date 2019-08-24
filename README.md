## USB RF Gateway on NRF24L01 or RFM69

  This is my mini project on STM32. Many makers use low cost radio transmitters NRF24L01 and RFM69 in their projects. This PCB should facilitate the use of radio modules for use as transmitters in USB devices. Can also be used as a RF-dongle for Raspberry Pi. 
  The basis of the device is the microcontroller STM32F042G6U6 in the case UFQFPN28 4x4 mm (smallest footprint controller enclosure I found on sale). 
  It is possible to download .bin files directly via USB, thanks to the built-in bootloader. For the whole, you’ll need to connect device in USB port on while holding down the “BOOT” button. I used STM32CubeProgrammer to download .bin file. 6-pin SWD Tag-Connect is also available for debugging.

### Features

- NRF24L01 SMD
- RFM69 868 or 915 MHz (to minimize antenna size, compared to antenna sizes for 433MHz)
- No programming probe needed for uploading firmware
- Tag-Connect for debugging
- Debugging LED on board
- The NRF24L01 version is perfect for the Gainta G1901 enclosure (if you order a 1 mm thick PCB)


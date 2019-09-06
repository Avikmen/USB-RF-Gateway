## USB RF Gateway on NRF24L01 or RFM69

<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190824_114225-01.jpeg" label="NRF24L01 SMD bare version">

  This is my mini project on STM32. Many makers use low cost radio transmitters NRF24L01 and RFM69 in their projects. This PCB should facilitate the use of radio modules for use as transmitters in USB devices. Can also be used as a RF-dongle for Raspberry Pi. 
  The basis of the device is the microcontroller STM32F042G6U6 in the case UFQFPN28 4x4 mm (smallest footprint controller enclosure I found on sale). 
  It is possible to download .bin files directly via USB, thanks to the built-in bootloader. For the whole, you’ll need to connect device in USB port on while holding down the “BOOT” button. I used STM32CubeProgrammer to download .bin file. 6-pin SWD Tag-Connect is also available for debugging.
  
<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190824_114612-01.jpeg" label="NRF24L01 SMD thermo shrink version">

<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190824_114648-01.jpeg" label="RFM69-868 thermo shrink and bare versions">

You can place the programmed and debugged device in the enclosure of Gainta G1901G or G1901C. I specifically tried to develop this device for such cases, because they are quite cheap and universal.

<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190906_161319-01.jpeg" label="In Gainta G1901C enclosure">

<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190906_161232-01.jpeg" label="In Gainta G1901C enclosure">

### Features

- NRF24L01 SMD
- RFM69 868 or 915 MHz (to minimize antenna size, compared to antenna sizes for 433MHz)
- No programming probe needed for uploading firmware
- Tag-Connect for debugging
- Debugging LED on board
- USB port ESD protection
- The NRF24L01 *(not tested RFM69 version)* version is perfect for the Gainta G1901C or 1901G enclosure (if you use a USB connector for deep PCB landing)
<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190906_160916-01.jpeg" label="USB connector for deep PCB landing">
<img width="400" src="https://github.com/Avikmen/USB-RF-Gateway/blob/master/Images/IMG_20190906_161319-01.jpeg" label="In Gainta G1901C enclosure">




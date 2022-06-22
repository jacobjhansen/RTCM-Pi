# RTCM-Pi
GNSS Base Station based on Raspberry Pi 4B

# Background
This project is intented to provide a design for creating a GNSS Reference Station using affordable and accessible hardware while maintaining high standards for functionality and reliability. The equipment used for this project is as follows:
1. [Raspberry Pi 4B](https://rpilocator.com/?country=US&cat=PI4)
2. [SparkFun GPS-RTK-SMA (u-blox ZED-F9P)](https://www.sparkfun.com/products/16481)
3. [RFD900x-US Telemetry Modem](https://irlock.com/collections/telemetry/products/rfd900x-us-telemetry-modem-fcc-approved)
4. [PiJuice HAT](https://www.sparkfun.com/products/14803)
5. [GNSS Multi-Band L1/L2 Antenna TOP106](https://www.sparkfun.com/products/17751)

Please note that other hardware/accessories are required for this project:
1. Soldering Iron [example](https://www.sparkfun.com/products/14228)
2. Break Away Headers [example](https://www.sparkfun.com/products/116)
3. Jumper Wires F/F [example](https://www.sparkfun.com/products/12796)
4. SMA Male to TNC Male [example](https://www.sparkfun.com/products/17833)
5. SMA Male to SMA Female [example](https://www.sparkfun.com/products/17495)
6. Outdoor Junction Box [example](https://www.amazon.com/dp/B000VYGMF2)
7. MicroSD Card

# Design
RTCM-Pi is connected as follows:
![RTCM-Pi Wiring Diagram](wireviz/rtcmpi.png "RTCM-Pi Design")

Where GPS-RTK-SMA RTCM refers to the RTCM Correction headers
![GPS-RTK-SMA RTCM](images/GPS-RTK-SMA-RTCM.png "GPS-RTK-SMA RTCM")

And where GPS-RTK-SMA UART refers to the standard UART headers on the right side of the board
![GPS-RTK-SMA UART](images/GPS-RTK-SMA-UART.png "GPS-RTK-SMA UART")
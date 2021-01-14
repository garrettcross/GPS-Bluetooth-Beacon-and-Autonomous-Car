# GPS-Bluetooth-Beacon-and-Autonomous-Car
CECS 490 - Senior Project:
  A beacon sends out its coordinates via Bluetooth and an autonomous car receives the coordinates and compares it with its own and moves towards the beacon.
  
# Authors
-Garrett  Cross
-William  Duong
-Terrence Hamilton
-Nicole   Reinkin

# Hardware
-TM4C123GH6PM Tiva C LaunchPad Microcontroller
-HC-05        Bluetooth Module
-NEO6MV2      GPS Moudule

# Brief Overview
1.  Interface GPS Module with Onboard UART Module
2.  (Optional) Output Coordinates on LCD Display
3.  Navigate Car to Hardcoded Coordinates
4.  Interface Bluetooth with Onboard UART Module
5.  (Optional) Input Coordinates via SmartPhone Bluetooth
6.  Transmit Coordinates from GPS via Bluetooth
7.  Receive Coordinates via Bluetooth
8.  (Optional) Output Destination Coordinates to LCD Display
9.  Navigate Car to Transmitted Coordinates (no obstacles)
10. (Optional) Add Ultrasonic Sensors for Obstacle Avoidance
11. (Optional) Navigate Car to Transmitted Coordinates
    while Avoiding Obstacles
12. (Optional) Transmit Car Status to SmartPhone via Bluetooth

# PlatformIO
## Prerequisites
- VS code
- PlatformIO Extension in VS code
- C/C++ and CMake
## Running the code
After installing VS code go to extensions and install PlatformIO. After installing the extension add the following libraries to the PlatformIO project (these must be re-entered manually into the PlatformIO project from the PlatformIO interface).

1. Arduino.h: The core Arduino library for the ESP8266 platform.
2. ESP8266WiFi.h: Library for managing Wi-Fi connections on ESP8266.
3. Firebase ESP Client.h: A Firebase library for the ESP8266.
4. Wire.h: The Arduino Wire library for I2C communication.
5. NTPClient.h and WiFiUdp.h: Libraries for getting the current time from an NTP server.

Navigate to <bold>'PlatformIO/Projects/Testing/src/main.cpp'</bold> and now go to the top right corner of the VS code and first build/compile the code and after the code is compiled successful, now upload the code onto NodeMCU(ESP8266) from the same top right corner. Once the code is uploaded on the IoT device you can check the weather it is working successfully using Serial Monitor.
### Note: 
It is best to run PlatformIO code on a Windows machine because when we tried it on a Linux machine, PlatformIO was unable to location a the COM(usb port) through which the code is uploaded to the NodeMCU(ESP8266) module.

# Cybersecurity : CSN150
Project: ESP32-CAM Camera Setup

## Purpose
In this lab, I configured the ESP32-CAM to create its own WiFi access point instead of connecting to an external network. This allowed me to connect directly to the ESP32 and access a web server hosted on it.

## Equipment
- ESP32-CAM  
- USB cable  
- Arduino IDE
  
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation and tools
https://lastminuteengineers.com/getting-started-with-esp32-cam/

Arduino IDE: https://www.arduino.cc/en/software/

ESP32 Board package: https://dl.espressif.com/dl/package_esp32_index.json

https://randomnerdtutorials.com/esp32-cam-access-point-ap-web-server/

##### Video 1: 
https://www.youtube.com/watch?v=4inE-n6kXSE

##### Other Links: 
https://lastminuteengineers.com/getting-started-with-esp32-cam/

##### AI GPTs used

## Steps I followed 
1. Opened Arduino IDE
2. Selected AI Thinker ESP32-CAM
3. Wrote Access Point code using WiFi.softAP()
4. Uploaded code using BOOT button
5. Opened Serial Monitor to get IP address
6. Connected to ESP32_AP WiFi
7. Accessed web server using browser
   
## Problems and Solutions
Problem 1: Upload failed with “Failed to connect to ESP32”
Solution: Held the BOOT button during upload to enter flash mode

Problem 2: No output in Serial Monitor
Solution: Pressed RESET button after opening Serial Monitor

Problem 3: “No Internet connection” message
Solution: Understood that ESP32 Access Point does not provide internet and continued to access the local server

## Final Report
In this lab, I successfully created a WiFi access point using the ESP32-CAM and hosted a web server. I connected directly to the ESP32 network and accessed the server through the browser. This demonstrated how the ESP32 can operate independently without needing an external internet connection.

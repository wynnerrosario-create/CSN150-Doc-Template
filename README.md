# Cybersecurity : CSN150
Project: ESP32-CAM Telegram Photo Sender

## Purpose
The purpose of this project was to use the ESP32-CAM to capture an image and send it through a Telegram bot. This demonstrates real-time communication between IoT devices and cloud-based messaging platforms.

## Equipment
- ESP32-CAM  
- USB cable  
- Arduino IDE
- Computer
  
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation and tools
https://lastminuteengineers.com/getting-started-with-esp32-cam/

Arduino IDE: https://www.arduino.cc/en/software/

ESP32 Board package: https://dl.espressif.com/dl/package_esp32_index.json

https://randomnerdtutorials.com/esp32-cam-access-point-ap-web-server/

##### Video 1: 


##### Other Links: 


##### AI GPTs used

## Steps I followed 
1. Created a Telegram bot using BotFather
2. Obtained the bot token
3. Retrieved my Chat ID using @userinfobot
4. Configured ESP32-CAM with WiFi credentials
5. Added bot token and Chat ID to the code
6. Uploaded the code using BOOT button
7. Verified connection using Serial Monitor
8. Sent /photo command through Telegram

## Problems and Solutions
Problem: ESP32 failed to upload code
Solution: Held BOOT button and reduced upload speed

Problem: Code errors (missing function, syntax issues)
Solution: Fixed code structure and added required functions

Problem: Telegram bot not responding
Solution: Corrected bot token, Chat ID, and loop logic

## Final Report
In this project, I successfully integrated the ESP32-CAM with a Telegram bot to capture and send images over the internet. This demonstrates how IoT devices can communicate with cloud services and mobile applications in real time. The project can be applied in areas such as security systems, remote monitoring, and automation.

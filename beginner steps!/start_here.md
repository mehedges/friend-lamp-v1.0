# Beginners Starting Point
Hello! Real talk, I did NOT have any experience with RaspberryPi before this project, but it can be a great intro on how to use one! It's important to keep in mind that RaspberryPi is nothing like an Arduino- it's essentially a mini computer. And what do all computers need? An operating system (called an "OS")! Before turnng on your Pi, you're going to need to flash that 8 GB SD card. This puts an OS on the card and therefore, on the Pi.

## Materials Needed Here
|  Soft/Hardware  |  Description   |  Cost   |  Link   |
|  -------------------   |  -------------------   |  -------------------   |  -------------------   |
|<img src="https://cdn-shop.adafruit.com/970x728/3400-00.jpg" width="100" />              |     Raspberry Pi 0       |     $15.00    |[Adafruit](https://www.adafruit.com/product/3400)|
|<img src="https://cdn-shop.adafruit.com/970x728/1294-03.jpg" width="100" />              |     8GB MicroSD Card     |     $9.95     |[Adafruit](https://www.adafruit.com/product/1294)|
| Raspberry Pi Imager                                                                     | Flashes the SD card with an operating system (OS)|  | [Raspberry Pi OS](https://www.raspberrypi.com/software/)|

## Reference Material
Here are some great articles & videos to help describe some steps further/help if you're stuck!

[Tom's Hardware- written by Avram Piltch](https://www.tomshardware.com/reviews/raspberry-pi-headless-setup-how-to,6028.html)

[Instructables- written by ArtsyEngineering](https://www.instructables.com/The-Ultimate-Headless-RPi-Zero-Setup-for-Beginners/)

[![IMAGE ALT TEXT HERE](https://github.com/mehedges/friend-lamp-v1.0/assets/102606124/85554f45-e1ec-4534-a1d5-b242bd6d9ea6)](https://www.youtube.com/watch?v=yn59qX-Td3E "YouTube guide by Data Slayer")

## Dictionary

**Flash/ing-** Writing data to the SD card. In this case, we are "writing" or "flashing" the OS onto the SD card.

**Headless-**

**Local Network-** Also called a "LAN" or local area network, consists of devices connected together closely either by ethernet or by WiFi. Basically, anything in your house that shares the same WiFi.

**WPA-** Stands for "WiFi Protected Access," which is the password/key that protects your WiFi (and ergo, devices on that WiFI network).

## Steps
1. Download the Raspberry Pi Imager and insert the SD card into your computer.
2. In the Raspberry Pi Imager, choose the board you have. Then, select either the Raspbery Pi OS or the Raspberry Pi OS Lite (Raspberry Pi OS (other)>Lite)
3. Select the storage device, which is the SD card (might appear as E:/ or something similar)
4. Here is where the steps diverege in what can be done:

| Option 1 | Option 2 |
|----------|----------|
|Select 'Next' and then 'Edit Settings' to add your WiFi information, raspberry pi username and password (for that device specifically)| Create a file for ssh and wpa configuration. This may require following the steps in either the Instructables guide or the YouTuve tutorial by Data Slayer. These were very helpful guides when I first started out.|

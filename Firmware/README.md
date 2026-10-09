**FIRMWARE**

The firmware is written for the Arduino IDE. Download the latest version of the Arduino IDE.

Below are some required libraries that I downloaded. You have to download these libraries in order for the firmware to work for this.
Required libraries:
Adafruit GFX Library
Adafruit SSD1306
Adafruit MPU6050
DHT sensor library

**Directions to install:**
1. Click _File_ --> _Preferences_ --> add the code below into the _Additional Board Managers URL_
* https://espressif.github.io/arduino-esp32/package_esp32_index.json
2. Select _Tools_ --> _Board_ --> _Board Manager_ --> search and download esp32 by Espressif Systems
3. Select _Tools_ --> _Board_ --> _esp32_ --> _XIAO_ESP32C3_ --> select the board's port under _Tools_ --> _Port_
4. Download the libraries above one by one (Click download all when asked about dependencies)
5. Open the Starbie.ino file and click Upload in the IDE

Under beginner settings is where I made my customizations. I changed the pet's starting stats, changed the bitmap pet, replaced the pet function on the radial menu with 'Shower', and gave it a star trail!

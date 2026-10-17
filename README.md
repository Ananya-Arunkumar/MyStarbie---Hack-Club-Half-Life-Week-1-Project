**Starbie**

Starbie is a tiny desk buddy built using a Seeed XIAO ESP32-C3, an OLED display, and motion and temperature sensors.

<img width="814" height="537" alt="Screenshot 2026-10-16 211552" src="https://github.com/user-attachments/assets/7c5079a8-cb99-464a-9267-ad16c12fb022" />

PCB Editor View

<img width="952" height="596" alt="Screenshot 2026-10-16 211637" src="https://github.com/user-attachments/assets/341e1560-a4e4-4458-a72f-45480d4b854d" />

3D view


**Features**
* Animated digital pet on a 0.96-inch OLED display
* Motion-controlled radial menu using an MPU6050 accelerometer
* Pet stats for joy, energy, and fullness
* Temperature and humidity readings using a DHT11 sensor
* Two buttons for interacting with the pet

**Hardware**
* Seeed XIAO ESP32-C3
* 0.96-inch SSD1306 OLED display
* MPU6050 accelerometer and gyroscope module (lets the thing know it's moving)
* DHT11 temperature and humidity sensor
* Two push buttons
* Starbie PCB

See BOM.csv for the bill of materials and PCB folder for the PCB design files.

**Software**
The PCB is designed using KiCad. The firmware is written for the Arduino IDE. (Refer firmware Folder)

**Building**
1. Gather the components listed in the bill of materials.
2. Assemble the circuit according to the schematic and wiring instructions.
3. Open the Starbie Arduino sketch in the Arduino IDE.
4. Install the required libraries.
5. Select the Seeed XIAO ESP32-C3 as the board.
6. Upload the sketch to the board.

Refer to the project guide for detailed assembly and setup instructions.

Project Files
Firmware/ — MyStarbie.ino
PCB/ — PCB layout, schematic, and KiCad project files
BOM.csv — Bill of materials

**Credits**
Starbie is based on the original project by SharKingStudios and Hack Club. Please refer to the original project repository and its license for attribution and reuse requirements.

**Starbie**

Starbie is a tiny desk buddy built using a Seeed XIAO ESP32-C3, an OLED display, and motion and temperature sensors.

<img width="814" height="537" alt="Screenshot 2026-10-16 211552" src="https://github.com/user-attachments/assets/7c5079a8-cb99-464a-9267-ad16c12fb022" />

PCB Editor View

<img width="952" height="596" alt="Screenshot 2026-10-16 211637" src="https://github.com/user-attachments/assets/341e1560-a4e4-4458-a72f-45480d4b854d" />

3D view


**Features**
Starbie is a digital Tamagotchi-esque pet who you can keep on your desk and take care of. It has a main radial menu in which it can detect movement using an accelerometer. The pet has a 4 main functions of eat, sleep, shower, and play and it has 3 main stats: joy, energy and fullness. You interact with the pet using the display and the 2 buttons. Along with that, Starbie can also detect the temperature and humidity of its surroundings. 

**Hardware**
Starbie was made with its PCB, obviously. It has a 0.96 inch OLED Display and 2 push buttons which all you to interact with the pet. It also has an MPU6050 accelerometer and gyroscope module which tells the pet where it is (Not like a GPS but rather like a "I'm moving fast right now". The brain of the Starbie is a XIAO ESP32-C3

See BOM.csv for the bill of materials and PCB folder for the PCB design files.

**Software**
The PCB is designed using KiCad. The firmware is written for the Arduino IDE. (Refer to firmware Folder)

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
Starbie is based on the original project by SharKingStudios and Hack Club. Please refer to the original project repository and its license for attribution, reuse, and other questions.

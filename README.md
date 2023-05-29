# Light Automation System
The Light Automation System Model is an embedded system that utilizes an LDR sensor,PIR sensor, LEDs, and wires along with a MCU to automate lighting based on ambient light conditions. 
This project aims to provide a hands-on demonstration of light automation principles using simple electronic components.
## Features
- Automatic control of LEDs based on the motion sensor(PIR)
- Real-time monitoring of light intensity using an LDR sensor.
- Easy-to-understand circuit code. 

## Usage
1. Power on the MCU and wait for the system to initialize.
2. The system will automatically monitor the motion and ambient light levels in the room.
3. When motion is detected and the ambient light level is below a threshold, the lights will be turned on.
4. After a period of inactivity or when the ambient light level rises above the threshold, the lights will be turned off.

## Steps
- Clone repository to download the code.
- Connect the PIR motion sensor and LDR sensor to the appropriate pins on the MCU according to the circuit diagram
- Connect the rest of the hardware components as per the wiki-page and run code using STMCubeMX and Keil MicroVision.

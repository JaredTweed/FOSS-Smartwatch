### General Plan
Building a screenless smart watch with accurate health detection. I would love for the open source community to help develop the data algorithms to improve sleep and excercize monitoring once developed.

I plan to make it have the option between being screenless and e-ink so it has a long battery. It will not have notifications or GPS (which uses lots if power) or anything not health/time related. A later version might have GPS but it would be off by default.

### Tools
- FreeCAD
- KiCAD

### Hardware Plan

Sensors
- PPG Sensor (e.g., MAX30102). Must include HR, HRV, and Sp0<sub>2</sub>.
- ECG capability (this is heart related info).
- Skin Temperature Sensor.
- 6-axis IMU (i.e., 3-axis accelerometer, 3-axis gryo). This measures motion.
- Barometer
- UV & Ambient Light Sensor (detects circadian rythm, outdoor activity).
- Bio-impedance Sensor

Remaining Prototype Parts
- Bluetooth
- Vibration
- Battery
- A large battery pack will be chargable via usb-c, and this pack should slide onto the band so you never have to take the band off.
- GPS (maybe)

Actual Parts Used
- nRF52840 (This is the lowest power MCU w/ bluetooth).
- 

Final Product
- Use "advanced nanoguard" spray to waterproof the circuit board.

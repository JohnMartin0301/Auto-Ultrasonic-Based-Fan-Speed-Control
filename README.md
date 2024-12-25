# AUTO-ULTRASONIC BASED FAN SPEED CONTROL





![auto-ultrasonic-based-fan-speed-control](https://github.com/user-attachments/assets/5808dd64-13d0-4bd1-a6c2-9f61a3bf1ff2)





## Features
1. **USB-Powered Portability**: Plug the device into a laptop, power bank, or adapter using the provided USB cable.
2. **Automatic Fan Control**: Adjusts fan speed based on object proximity.
3. **OLED Display**: Provides real-time feedback on distance and fan speed.
4. **Compact and Durable Design**: Enclosed in a sleek casing with all components soldered onto a PCB.





## Components
1. **Arduino Nano**: The brain of the system.
2. **Ultrasonic Sensor (HC-SR04)**: Measures distance.
3. **0.96-inch OLED Display**: Displays real-time data.
4. **10 Ohm Resistor**: Protects the circuit.
5. **NPN Transistor**: Drives the 5V DC fan.
6. **5V DC Fan**: Operates at various speeds.
7. **Mini USB Cable Type A**: For power input.





## Power Requirements
- **Input Voltage**: 5V DC  
- The device is powered via a USB connection, which can be plugged into:
  - Laptop
  - Power Bank
  - Wall Adapter
 




## How It Works
1. The ultrasonic sensor detects the distance of an object in front of it.
2. Based on the distance:
   - **5–10 cm**: Fan speed is set to LOW.
   - **10–15 cm**: Fan speed is set to MEDIUM.
   - **15–20 cm**: Fan speed is set to HIGH.
   - **Above 20 cm or no object**: Fan turns OFF.
3. The OLED display updates to show the current distance and fan speed in real time.






## Credits
- **Developer**: John Carlo D. Martin  
- **Project Name**: Auto-Ultrasonic Based Fan Speed Control  
- **Date**: 2024
